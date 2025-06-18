<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .form-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 16px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        textarea {
            resize: vertical;
            min-height: 100px;
        }
        button {
            background-color: #007bff;
            color: #fff;
            padding: 12px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover:not(:disabled) {
            background-color: #0056b3;
        }
        button:disabled {
            background-color: #cccccc;
            cursor: not-allowed;
        }
        .hidden {
            display: none;
        }
        .error {
            color: red;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2>Contact Us</h2>
        <form id="contactForm" action="https://formsubmit.co/achadha08@gmail.com" method="POST" enctype="multipart/form-data">
            <!-- Honeypot field to trap spambots -->
            <input type="text" name="_honey" class="hidden">
            <!-- Custom email subject -->
            <input type="hidden" name="_subject" value="New Contact Form Submission">
            <!-- CC additional email addresses -->
            <input type="hidden" name="_cc" value="another@email.com">
            <!-- Disable reCAPTCHA (remove if you want reCAPTCHA enabled) -->
            <input type="hidden" name="_captcha" value="false">
            
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required placeholder="Your Name">
            
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required placeholder="Your Email">
            
            <label for="message">Message</label>
            <textarea id="message" name="message" required placeholder="Your Message"></textarea>
            
            <label for="attachment">Attach a File (Optional)</label>
            <input type="file" id="attachment" name="attachment" accept="image/png, image/jpeg, application/pdf">
            
            <button type="submit" id="submitButton">Send Message</button>
            <p id="formStatus" class="error"></p>
        </form>
    </div>

    <script>
        const form = document.getElementById('contactForm');
        const submitButton = document.getElementById('submitButton');
        const formStatus = document.getElementById('formStatus');

        form.addEventListener('submit', async (event) => {
            event.preventDefault(); // Prevent default form submission
            submitButton.disabled = true;
            submitButton.textContent = 'Sending...';
            formStatus.textContent = '';

            try {
                const formData = new FormData(form);
                const response = await fetch(form.action, {
                    method: 'POST',
                    body: formData,
                    headers: {
                        'Accept': 'application/json'
                    }
                });

                if (response.ok) {
                    formStatus.style.color = 'green';
                    formStatus.textContent = 'Message sent successfully!';
                    form.reset();
                } else {
                    throw new Error('Form submission failed');
                }
            } catch (error) {
                formStatus.textContent = 'Error sending message. Please try again later.';
                console.error('Submission error:', error);
            } finally {
                submitButton.disabled = false;
                submitButton.textContent = 'Send Message';
            }
        });
    </script>
</body>
</html>

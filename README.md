<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HairMaxx Solutions - Fight Hair Loss Effectively</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#3b82f6',
                        secondary: '#10b981',
                        dark: '#1e293b',
                        light: '#f8fafc',
                    }
                }
            }
        }
    </script>
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, rgba(59, 130, 246, 0.8) 0%, rgba(16, 185, 129, 0.8) 100%);
        }
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .hair-type-btn.active {
            background-color: #3b82f6;
            color: white;
        }
        .progress-bar {
            transition: width 0.5s ease-in-out;
        }
    </style>
</head>
<body class="bg-light font-sans">
    <!-- Header -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fas fa-cut text-primary text-2xl"></i>
                <h1 class="text-xl font-bold text-dark">HairMaxx <span class="text-primary">Solutions</span></h1>
            </div>
            <nav class="hidden md:flex space-x-8">
                <a href="#causes" class="text-dark hover:text-primary transition">Causes</a>
                <a href="#solutions" class="text-dark hover:text-primary transition">Solutions</a>
                <a href="#products" class="text-dark hover:text-primary transition">Products</a>
                <a href="#faq" class="text-dark hover:text-primary transition">FAQ</a>
            </nav>
            <button class="md:hidden text-dark" id="menu-toggle">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
        <div class="md:hidden hidden bg-white py-2 px-4 shadow-md" id="mobile-menu">
            <a href="#causes" class="block py-2 text-dark hover:text-primary transition">Causes</a>
            <a href="#solutions" class="block py-2 text-dark hover:text-primary transition">Solutions</a>
            <a href="#products" class="block py-2 text-dark hover:text-primary transition">Products</a>
            <a href="#faq" class="block py-2 text-dark hover:text-primary transition">FAQ</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-gradient text-white py-16 md:py-24">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-8 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold mb-4">Maximize Your Hair Growth Potential</h1>
                <p class="text-xl mb-8">Discover science-backed solutions and top-rated products to combat hair loss effectively.</p>
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                    <a href="#products" class="bg-white text-primary font-bold py-3 px-6 rounded-full hover:bg-opacity-90 transition text-center">Shop Recommended Products</a>
                    <a href="#quiz" class="bg-transparent border-2 border-white text-white font-bold py-3 px-6 rounded-full hover:bg-white hover:text-primary transition text-center">Take Hair Quiz</a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <img src="/api/placeholder/400/320" alt="placeholder">
            </div>
        </div>
    </section>

    <!-- Hair Loss Stats -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-dark mb-12">Understanding Hair Loss</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-light p-6 rounded-lg shadow text-center">
                    <div class="text-primary text-5xl font-bold mb-2">50%</div>
                    <h3 class="text-xl font-semibold mb-2">Of Men by Age 50</h3>
                    <p class="text-gray-600">Experience noticeable hair loss according to the American Hair Loss Association.</p>
                </div>
                <div class="bg-light p-6 rounded-lg shadow text-center">
                    <div class="text-primary text-5xl font-bold mb-2">40%</div>
                    <h3 class="text-xl font-semibold mb-2">Of Women</h3>
                    <p class="text-gray-600">Show visible signs of hair loss by age 40, often due to hormonal changes.</p>
                </div>
                <div class="bg-light p-6 rounded-lg shadow text-center">
                    <div class="text-primary text-5xl font-bold mb-2">100+</div>
                    <h3 class="text-xl font-semibold mb-2">Hairs Daily</h3>
                    <p class="text-gray-600">Losing 100-150 hairs per day is normal. More than that may indicate a problem.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Causes Section -->
    <section id="causes" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-dark mb-4">Common Causes of Hair Loss</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">Understanding the root cause is the first step toward effective treatment.</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow hover:shadow-md transition">
                    <div class="bg-primary bg-opacity-10 w-12 h-12 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-dna text-primary text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Genetics (Androgenetic Alopecia)</h3>
                    <p class="text-gray-600">The most common cause, affecting both men and women. It's hereditary and often develops gradually.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow hover:shadow-md transition">
                    <div class="bg-primary bg-opacity-10 w-12 h-12 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-stress text-primary text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Hormonal Changes</h3>
                    <p class="text-gray-600">Pregnancy, menopause, thyroid problems, and other hormonal imbalances can cause temporary or permanent hair loss.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow hover:shadow-md transition">
                    <div class="bg-primary bg-opacity-10 w-12 h-12 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-pills text-primary text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Medical Conditions & Medications</h3>
                    <p class="text-gray-600">Alopecia areata, scalp infections, and drugs for cancer, arthritis, depression can lead to hair loss.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow hover:shadow-md transition">
                    <div class="bg-primary bg-opacity-10 w-12 h-12 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-heartbeat text-primary text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Nutritional Deficiencies</h3>
                    <p class="text-gray-600">Lack of protein, iron, zinc, vitamin D, and other nutrients can affect hair growth cycles.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow hover:shadow-md transition">
                    <div class="bg-primary bg-opacity-10 w-12 h-12 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-brain text-primary text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Stress & Trauma</h3>
                    <p class="text-gray-600">Physical or emotional stress can trigger temporary hair shedding (telogen effluvium).</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow hover:shadow-md transition">
                    <div class="bg-primary bg-opacity-10 w-12 h-12 rounded-full flex items-center justify-center mb-4">
                        <i class="fas fa-cut text-primary text-xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Hairstyling & Treatments</h3>
                    <p class="text-gray-600">Tight hairstyles, harsh chemicals, and excessive heat can cause traction alopecia.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Solutions Section -->
    <section id="solutions" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-dark mb-4">Effective Solutions for Hair Loss</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">From medical treatments to lifestyle changes, explore proven methods to combat hair loss.</p>
            
            <div class="flex flex-col md:flex-row mb-12 bg-gray-50 rounded-lg overflow-hidden">
                <div class="md:w-1/2 p-8">
                    <h3 class="text-2xl font-semibold mb-4">Medical Treatments</h3>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="bg-primary text-white rounded-full w-6 h-6 flex items-center justify-center mr-3 mt-1 flex-shrink-0">1</div>
                            <div>
                                <h4 class="font-semibold">Minoxidil (Rogaine)</h4>
                                <p class="text-gray-600">Over-the-counter topical treatment that stimulates hair follicles and slows hair loss.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-primary text-white rounded-full w-6 h-6 flex items-center justify-center mr-3 mt-1 flex-shrink-0">2</div>
                            <div>
                                <h4 class="font-semibold">Finasteride (Propecia)</h4>
                                <p class="text-gray-600">Prescription pill for men that blocks the hormone responsible for hair loss.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-primary text-white rounded-full w-6 h-6 flex items-center justify-center mr-3 mt-1 flex-shrink-0">3</div>
                            <div>
                                <h4 class="font-semibold">Low-Level Laser Therapy</h4>
                                <p class="text-gray-600">FDA-cleared devices that use light energy to stimulate hair growth.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-primary text-white rounded-full w-6 h-6 flex items-center justify-center mr-3 mt-1 flex-shrink-0">4</div>
                            <div>
                                <h4 class="font-semibold">Platelet-Rich Plasma (PRP)</h4>
                                <p class="text-gray-600">Injection treatment using your own blood's growth factors to stimulate follicles.</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2 bg-primary bg-opacity-10 p-8">
                    <h3 class="text-2xl font-semibold mb-4">Natural & Lifestyle Approaches</h3>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <div class="bg-secondary text-white rounded-full w-6 h-6 flex items-center justify-center mr-3 mt-1 flex-shrink-0">1</div>
                            <div>
                                <h4 class="font-semibold">Nutrition Optimization</h4>
                                <p class="text-gray-600">Ensure adequate protein, iron, zinc, biotin, and vitamins D, E, and B complex.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-secondary text-white rounded-full w-6 h-6 flex items-center justify-center mr-3 mt-1 flex-shrink-0">2</div>
                            <div>
                                <h4 class="font-semibold">Scalp Massage</h4>
                                <p class="text-gray-600">Improves circulation and may promote hair thickness when done regularly.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-secondary text-white rounded-full w-6 h-6 flex items-center justify-center mr-3 mt-1 flex-shrink-0">3</div>
                            <div>
                                <h4 class="font-semibold">Stress Management</h4>
                                <p class="text-gray-600">Yoga, meditation, and adequate sleep can help reduce stress-related hair loss.</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="bg-secondary text-white rounded-full w-6 h-6 flex items-center justify-center mr-3 mt-1 flex-shrink-0">4</div>
                            <div>
                                <h4 class="font-semibold">Gentle Hair Care</h4>
                                <p class="text-gray-600">Avoid tight hairstyles, limit heat styling, and use mild, nourishing hair products.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="bg-gray-50 rounded-lg p-8">
                <h3 class="text-2xl font-semibold mb-6 text-center">Hair Growth Timeline</h3>
                <div class="max-w-4xl mx-auto">
                    <div class="flex justify-between mb-2">
                        <span class="text-sm font-medium">0 Months</span>
                        <span class="text-sm font-medium">3 Months</span>
                        <span class="text-sm font-medium">6 Months</span>
                        <span class="text-sm font-medium">12+ Months</span>
                    </div>
                    <div class="w-full bg-gray-200 rounded-full h-4 mb-6">
                        <div class="progress-bar bg-primary h-4 rounded-full" style="width: 0%" id="progress-bar"></div>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-4 gap-4">
                        <div class="text-center">
                            <div class="bg-white p-3 rounded-lg shadow mb-2">
                                <i class="fas fa-search text-primary text-2xl"></i>
                            </div>
                            <p class="text-sm">Diagnosis & Treatment Begins</p>
                        </div>
                        <div class="text-center">
                            <div class="bg-white p-3 rounded-lg shadow mb-2">
                                <i class="fas fa-leaf text-primary text-2xl"></i>
                            </div>
                            <p class="text-sm">Reduced Shedding</p>
                        </div>
                        <div class="text-center">
                            <div class="bg-white p-3 rounded-lg shadow mb-2">
                                <i class="fas fa-seedling text-primary text-2xl"></i>
                            </div>
                            <p class="text-sm">New Hair Growth</p>
                        </div>
                        <div class="text-center">
                            <div class="bg-white p-3 rounded-lg shadow mb-2">
                                <i class="fas fa-award text-primary text-2xl"></i>
                            </div>
                            <p class="text-sm">Full Results Visible</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-dark mb-4">Top-Rated Hair Loss Products</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">These Amazon products have helped thousands combat hair loss effectively.</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card transition duration-300">
                    <div class="relative">
                        <img src="/api/placeholder/320/200" alt="Pumpkin Seed Oil" class="w-full h-64 object-contain">
                        <div class="absolute top-2 right-2 bg-primary text-white text-xs font-bold px-2 py-1 rounded">ESSENTIAL OIL</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Seven Minerals Pumpkin Seed Oil</h3>
                        <div class="flex items-center mb-2">
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                            <span class="text-gray-600 ml-2">143 reviews</span>
                        </div>
                        <p class="text-gray-600 mb-4">Rich in vitamins and nutrients, this Organic Pumpkin Seed Oil for hair deeply moisturizes, strengthens, and promotes hair growth.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xl font-bold text-dark">$24.95</span>
                            <a href="#" class="bg-primary text-white px-4 py-2 rounded hover:bg-blue-600 transition">View on Amazon</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 2 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card transition duration-300">
                    <div class="relative">
                        <img src="/api/placeholder/320/200" alt="Saw Palmetto Extract" class="w-full h-64 object-contain">
                        <div class="absolute top-2 right-2 bg-secondary text-white text-xs font-bold px-2 py-1 rounded">HERB</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Extra Strength Saw Palmetto Extract</h3>
                        <div class="flex items-center mb-2">
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                            <span class="text-gray-600 ml-2">10,653 reviews</span>
                        </div>
                        <p class="text-gray-600 mb-4">Designed for both Men & Women, our extract of saw palmetto berries may block 5-alpha-reductase, an enzyme that converts testosterone to DHT.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xl font-bold text-dark">$12.99</span>
                            <a href="#" class="bg-primary text-white px-4 py-2 rounded hover:bg-blue-600 transition">View on Amazon</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 3 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card transition duration-300">
                    <div class="relative">
                        <img src="/api/placeholder/320/200" alt="Derma Roller" class="w-full h-64 object-contain">
                        <div class="absolute top-2 right-2 bg-primary text-white text-xs font-bold px-2 py-1 rounded">TECHNOLOGY</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Titanium Microneedles Derma Roller</h3>
                        <div class="flex items-center mb-2">
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                            <span class="text-gray-600 ml-2">288 reviews</span>
                        </div>
                        <p class="text-gray-600 mb-4">This titanium derma roller for hair growth gently stimulates the scalp with fine needles, improving circulation and supporting healthier, fuller-looking hair.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xl font-bold text-dark">$9.99</span>
                            <a href="#" class="bg-primary text-white px-4 py-2 rounded hover:bg-blue-600 transition">View on Amazon</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 4 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card transition duration-300">
                    <div class="relative">
                        <img src="/api/placeholder/320/200" alt="Biotin Supplement" class="w-full h-64 object-contain">
                        <div class="absolute top-2 right-2 bg-secondary text-white text-xs font-bold px-2 py-1 rounded">SUPPLEMENT</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Biotin 10000mcg Supplement</h3>
                        <div class="flex items-center mb-2">
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                            <span class="text-gray-600 ml-2">686 reviews</span>
                        </div>
                        <p class="text-gray-600 mb-4">Biotin softgels expertly crafted to nurture your hair, skin, and nails, helping you radiate confidence.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xl font-bold text-dark">$9.79</span>
                            <a href="#" class="bg-primary text-white px-4 py-2 rounded hover:bg-blue-600 transition">View on Amazon</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 5 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card transition duration-300">
                    <div class="relative">
                        <img src="/api/placeholder/320/200" alt="PURA D'OR Shampoo" class="w-full h-64 object-contain">
                        <div class="absolute top-2 right-2 bg-primary text-white text-xs font-bold px-2 py-1 rounded">SHAMPOO</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">PURA D'OR Hair Thinning Therapy Shampoo</h3>
                        <div class="flex items-center mb-2">
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                            <span class="text-gray-600 ml-2">29,319 reviews</span>
                        </div>
                        <p class="text-gray-600 mb-4">Gold standard shampoo with DHT blockers, biotin, and natural ingredients to reduce hair thinning.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xl font-bold text-dark">$29.99</span>
                            <a href="#" class="bg-primary text-white px-4 py-2 rounded hover:bg-blue-600 transition">View on Amazon</a>
                        </div>
                    </div>
                </div>
                
                <!-- Product 6 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden product-card transition duration-300">
                    <div class="relative">
                        <img src="/api/placeholder/320/200" alt="Scalp Massager" class="w-full h-64 object-contain">
                        <div class="absolute top-2 right-2 bg-secondary text-white text-xs font-bold px-2 py-1 rounded">TOOL</div>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold mb-2">Silicone Scalp Massager</h3>
                        <div class="flex items-center mb-2">
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                            <span class="text-gray-600 ml-2">1,211 reviews</span>
                        </div>
                        <p class="text-gray-600 mb-4">Gentle silicone bristles stimulate blood flow to hair follicles while cleansing the scalp.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-xl font-bold text-dark">$6.99</span>
                            <a href="#" class="bg-primary text-white px-4 py-2 rounded hover:bg-blue-600 transition">View on Amazon</a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 text-center">
                <a href="#" class="inline-block bg-dark text-white px-6 py-3 rounded-lg hover:bg-opacity-90 transition">View More Natural Hair Growth Products</a>
            </div>
        </div>
    </section>

    <!-- Hair Quiz Section -->
    <section id="quiz" class="py-16 bg-white">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-3xl font-bold text-center text-dark mb-4">Personalized Hair Loss Solution Finder</h2>
            <p class="text-center text-gray-600 mb-12">Answer a few questions to get customized product recommendations.</p>
            
            <div class="bg-

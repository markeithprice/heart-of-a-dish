<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heart of A Dish - Meal Ideas</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* Custom styles to apply the Inter font */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- Main Container -->
    <div class="container mx-auto px-4 py-8 md:py-12">

        <!-- Header Section -->
        <header class="text-center mb-12">
            <h1 class="text-4xl md:text-5xl font-bold text-slate-900">Heart of A Dish</h1>
            <h2 class="mt-4 text-2xl md:text-3xl font-semibold text-slate-700">Meal Ideas</h2>
            <p class="mt-2 text-lg text-slate-600">by Heart Motivation & Markeith Price</p>
        </header>

        <!-- Meal Sections -->
        <div class="space-y-16">

            <!-- Breakfast Ideas Section -->
            <section id="breakfast">
                <h2 class="text-3xl font-bold text-slate-900 mb-6">Breakfast Ideas</h2>
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <!-- Table container for horizontal scrolling on small screens -->
                    <div class="overflow-x-auto">
                        <table class="w-full text-sm text-left text-slate-600">
                            <thead class="text-xs text-slate-700 uppercase bg-slate-100 sticky top-0">
                                <tr>
                                    <th scope="col" class="px-6 py-3">Meal Idea</th>
                                    <th scope="col" class="px-6 py-3">Approx. Calories</th>
                                    <th scope="col" class="px-6 py-3">Protein (g)</th>
                                    <th scope="col" class="px-6 py-3">Carbs (g)</th>
                                    <th scope="col" class="px-6 py-3">Fat (g)</th>
                                    <th scope="col" class="px-6 py-3 min-w-[300px]">Key Vitamins & Minerals</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Oatmeal with Berries and Nuts (Certified Gluten-Free Oats)</td>
                                    <td class="px-6 py-4">300-350</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">40-50</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">Manganese, Phosphorus, Magnesium, Vitamin C, Antioxidants</td>
                                </tr>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Greek Yogurt with Gluten-Free Granola and Fruit</td>
                                    <td class="px-6 py-4">250-300</td>
                                    <td class="px-6 py-4">15-20</td>
                                    <td class="px-6 py-4">30-40</td>
                                    <td class="px-6 py-4">5-10</td>
                                    <td class="px-6 py-4">Calcium, Vitamin D (if fortified), Potassium, Vitamin C</td>
                                </tr>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Scrambled Eggs with Avocado, Sliced Fruit, and Berries</td>
                                    <td class="px-6 py-4">380-450</td>
                                    <td class="px-6 py-4">15-20</td>
                                    <td class="px-6 py-4">30-40</td>
                                    <td class="px-6 py-4">20-25</td>
                                    <td class="px-6 py-4">Vitamin D, Choline, B Vitamins, Vitamin E, Potassium, Vitamin C, Antioxidants</td>
                                </tr>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Smoothie with Spinach, Banana, Almond Milk, and Protein Powder</td>
                                    <td class="px-6 py-4">300-350</td>
                                    <td class="px-6 py-4">20-30</td>
                                    <td class="px-6 py-4">30-40</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">Vitamin K, Vitamin A, Potassium, Calcium</td>
                                </tr>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Gluten-Free Banana Sweet Potato Oatmeal Pancakes with Fruit</td>
                                    <td class="px-6 py-4">300-350</td>
                                    <td class="px-6 py-4">10-12</td>
                                    <td class="px-6 py-4">50-60</td>
                                    <td class="px-6 py-4">5-10</td>
                                    <td class="px-6 py-4">B Vitamins, Manganese, Vitamin A, Vitamin C</td>
                                </tr>
                                <tr class="bg-white hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Gluten-Free Banana Sweet Potato Oatmeal Waffles with Nut Butter and Banana</td>
                                    <td class="px-6 py-4">300-350</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">40-50</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">Manganese, B Vitamins, Vitamin A, Vitamin C, Potassium</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </section>

            <!-- Lunch & Dinner Ideas Section -->
            <section id="lunch-dinner">
                <h2 class="text-3xl font-bold text-slate-900 mb-6">Lunch & Dinner Ideas</h2>
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <div class="overflow-x-auto">
                        <table class="w-full text-sm text-left text-slate-600">
                            <thead class="text-xs text-slate-700 uppercase bg-slate-100 sticky top-0">
                                <tr>
                                    <th scope="col" class="px-6 py-3">Meal Idea</th>
                                    <th scope="col" class="px-6 py-3">Approx. Calories</th>
                                    <th scope="col" class="px-6 py-3">Protein (g)</th>
                                    <th scope="col" class="px-6 py-3">Carbs (g)</th>
                                    <th scope="col" class="px-6 py-3">Fat (g)</th>
                                    <th scope="col" class="px-6 py-3 min-w-[300px]">Key Vitamins & Minerals</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Grilled Chicken Salad with Mixed Greens, Vegetables, and Light Vinaigrette</td>
                                    <td class="px-6 py-4">350-400</td>
                                    <td class="px-6 py-4">30-35</td>
                                    <td class="px-6 py-4">20-25</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">Varies widely depending on vegetables (Vitamin A, C, K, Folate)</td>
                                </tr>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Tuna Salad (made with Greek yogurt) on Gluten-Free Crackers</td>
                                    <td class="px-6 py-4">300-350</td>
                                    <td class="px-6 py-4">20-25</td>
                                    <td class="px-6 py-4">20-25</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">Vitamin D, B12, Selenium</td>
                                </tr>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Quinoa Salad with Roasted Vegetables and Chickpeas</td>
                                    <td class="px-6 py-4">350-400</td>
                                    <td class="px-6 py-4">12-15</td>
                                    <td class="px-6 py-4">50-60</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">Manganese, Magnesium, Fiber, Varies with vegetables</td>
                                </tr>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Chicken and Vegetable Skewers with a Side of Quinoa or White Rice</td>
                                    <td class="px-6 py-4">350-400</td>
                                    <td class="px-6 py-4">25-30</td>
                                    <td class="px-6 py-4">30-40</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">Varies with vegetables (B Vitamins, Vitamin C)</td>
                                </tr>
                                 <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Baked Chicken Breast with Roasted Asparagus and Quinoa</td>
                                    <td class="px-6 py-4">400-450</td>
                                    <td class="px-6 py-4">35-40</td>
                                    <td class="px-6 py-4">30-40</td>
                                    <td class="px-6 py-4">10-15</td>
                                    <td class="px-6 py-4">Selenium, B Vitamins, Vitamin K, Manganese</td>
                                </tr>
                                <tr class="bg-white border-b hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Baked Salmon with Roasted Regular or Sweet Potato and Green Beans</td>
                                    <td class="px-6 py-4">400-480</td>
                                    <td class="px-6 py-4">30-35</td>
                                    <td class="px-6 py-4">30-50</td>
                                    <td class="px-6 py-4">15-20</td>
                                    <td class="px-6 py-4">Vitamin D, Omega-3 fatty acids, Vitamin C, Beta-carotene (sweet potato)</td>
                                </tr>
                                <tr class="bg-white hover:bg-slate-50">
                                    <td class="px-6 py-4 font-medium text-slate-900">Chicken and Vegetable Curry with White or Brown Rice</td>
                                    <td class="px-6 py-4">400-450</td>
                                    <td class="px-6 py-4">30-35</td>
                                    <td class="px-6 py-4">40-50</td>
                                    <td class="px-6 py-4">15-20</td>
                                    <td class="px-6 py-4">Varies with vegetables and spices</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </section>

            <!-- Snacks & Treats Section -->
            <section id="snacks">
                <h2 class="text-3xl font-bold text-slate-900 mb-6">Snacks & Treats</h2>
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <div class="overflow-x-auto">
                        <table class="w-full text-sm text-left text-slate-600">
                            <thead class="text-xs text-slate-700 uppercase bg-slate-100 sticky top-0">
                                <tr>
                                    <th scope="col" class="px-6 py-3">Meal Idea</th>
                                    <th scope="col" class="px-6 py-3">Approx. Calories</th>
                                    <th scope="col" class="px-6 py-3">Protein (g)</th>
                                    <th scope="col" class="px-6 py-3">Carbs (g)</th>
                                    <th scope="col" class="px-6 py-3">Fat (g)</th>
                                    <th scope="col" class="px-6 py-3 min-w-[300px]">Key Vitamins & Minerals</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Apple Slices with Almond Butter</td><td class="px-6 py-4">200</td><td class="px-6 py-4">7</td><td class="px-6 py-4">20</td><td class="px-6 py-4">12</td><td class="px-6 py-4">Vitamin C, Vitamin E</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Hard-Boiled Eggs</td><td class="px-6 py-4">70</td><td class="px-6 py-4">6</td><td class="px-6 py-4">&lt;1</td><td class="px-6 py-4">5</td><td class="px-6 py-4">Vitamin D, B12</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Greek Yogurt with a Sprinkle of Nuts</td><td class="px-6 py-4">150</td><td class="px-6 py-4">15</td><td class="px-6 py-4">10</td><td class="px-6 py-4">5</td><td class="px-6 py-4">Calcium</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">A Handful of Almonds</td><td class="px-6 py-4">170</td><td class="px-6 py-4">6</td><td class="px-6 py-4">6</td><td class="px-6 py-4">15</td><td class="px-6 py-4">Vitamin E, Magnesium</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Dark Chocolate (Small Square)</td><td class="px-6 py-4">70</td><td class="px-6 py-4">1</td><td class="px-6 py-4">8</td><td class="px-6 py-4">5</td><td class="px-6 py-4">Antioxidants</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Baked Apple with Cinnamon</td><td class="px-6 py-4">100</td><td class="px-6 py-4">&lt;1</td><td class="px-6 py-4">25</td><td class="px-6 py-4">&lt;1</td><td class="px-6 py-4">Vitamin C, Fiber</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Frozen Berries</td><td class="px-6 py-4">60</td><td class="px-6 py-4">&lt;1</td><td class="px-6 py-4">15</td><td class="px-6 py-4">&lt;1</td><td class="px-6 py-4">Vitamin C, Antioxidants</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Homemade Energy Balls (Gluten-Free Oats, Nuts, Dates)</td><td class="px-6 py-4">100 (per ball)</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Greek Yogurt with Honey and a Sprinkle of Gluten-Free Granola</td><td class="px-6 py-4">180</td><td class="px-6 py-4">15</td><td class="px-6 py-4">20</td><td class="px-6 py-4">5</td><td class="px-6 py-4">Calcium</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Fruit Skewers with a Drizzle of Dark Chocolate</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies by fruit and chocolate</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Nice Cream (Blended Frozen Banana)</td><td class="px-6 py-4">100</td><td class="px-6 py-4">1</td><td class="px-6 py-4">25</td><td class="px-6 py-4">&lt;1</td><td class="px-6 py-4">Potassium</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">A Small Handful of Trail Mix (Nuts, Seeds, Dried Fruit - no added sugar)</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies</td><td class="px-6 py-4">Varies by ingredients</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Herbal Tea with a Touch of Honey</td><td class="px-6 py-4">Minimal</td><td class="px-6 py-4">Trace</td><td class="px-6 py-4">Trace</td><td class="px-6 py-4">Trace</td><td class="px-6 py-4">Minimal</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Sliced Apple and Honey</td><td class="px-6 py-4">100-120</td><td class="px-6 py-4">&lt;1</td><td class="px-6 py-4">25-30</td><td class="px-6 py-4">&lt;1</td><td class="px-6 py-4">Vitamin C</td></tr>
                                <tr class="bg-white border-b hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Sliced Apple and Cashew Butter</td><td class="px-6 py-4">200-250</td><td class="px-6 py-4">5-7</td><td class="px-6 py-4">25-30</td><td class="px-6 py-4">10-15</td><td class="px-6 py-4">Vitamin C, Magnesium, Phosphorus</td></tr>
                                <tr class="bg-white hover:bg-slate-50"><td class="px-6 py-4 font-medium text-slate-900">Plain Rice Cake with Cashew Butter</td><td class="px-6 py-4">150-180</td><td class="px-6 py-4">4-6</td><td class="px-6 py-4">20-25</td><td class="px-6 py-4">8-10</td><td class="px-6 py-4">Magnesium, Phosphorus</td></tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </section>

        </div>
        
        <!-- Footer Section -->
        <footer class="text-center mt-16">
            <p class="text-slate-500">&copy; 2024 Heart Motivation & Markeith Price. All Rights Reserved.</p>
        </footer>

    </div>

</body>
</html>


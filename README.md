<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INFINITE STUDY - Admission Registration</title>
    <!-- Inter font from Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom styles for subtle enhancements beyond default Tailwind */
        body {
            font-family: 'Inter', sans-serif; /* Apply Inter font */
            background-color: #f0f2f5; /* Light gray background */
        }
        /* Style for the button hover effect */
        button:hover {
            box-shadow: 0 4px 15px rgba(0, 123, 255, 0.3); /* Subtle blue shadow on hover */
        }
        /* Custom focus style for inputs */
        input:focus, select:focus, textarea:focus {
            outline: none;
            border-color: #3b82f6; /* Blue-500 from Tailwind */
            box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.2); /* Light blue ring */
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen p-4 sm:p-6 lg:p-8">
    <div class="bg-white p-6 sm:p-8 lg:p-10 rounded-xl shadow-2xl w-full max-w-xl md:max-w-2xl lg:max-w-3xl border border-gray-200 overflow-y-auto max-h-[95vh]">
        <h2 class="text-3xl sm:text-4xl font-extrabold text-center text-gray-800 mb-8 sm:mb-10 leading-tight">
            <span class="text-blue-600">INFINITE STUDY</span><br>Admission Registration
        </h2>
        <form action="#" method="POST" class="space-y-6 sm:space-y-8">
            <!-- Student Information -->
            <div>
                <label for="fullName" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Full Name (as per official records):</label>
                <input type="text" id="fullName" name="fullName" placeholder="e.g., John Doe" required
                       class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
            </div>

  <div>
                <label for="dob" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required
                       class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
            </div>

   <div>
                <label class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Gender:</label>
                <div class="flex flex-wrap gap-x-6 gap-y-2">
                    <div class="flex items-center">
                        <input type="radio" id="male" name="gender" value="male" required
                               class="focus:ring-blue-500 h-4 w-4 text-blue-600 border-gray-300 rounded-full cursor-pointer">
                        <label for="male" class="ml-2 block text-base text-gray-700">Male</label>
                    </div>
                    <div class="flex items-center">
                        <input type="radio" id="female" name="gender" value="female"
                               class="focus:ring-blue-500 h-4 w-4 text-blue-600 border-gray-300 rounded-full cursor-pointer">
                        <label for="female" class="ml-2 block text-base text-gray-700">Female</label>
                    </div>
                    <div class="flex items-center">
                        <input type="radio" id="other" name="gender" value="other"
                               class="focus:ring-blue-500 h-4 w-4 text-blue-600 border-gray-300 rounded-full cursor-pointer">
                        <label for="other" class="ml-2 block text-base text-gray-700">Other</label>
                    </div>
                </div>
            </div>

            <!-- Contact Information -->
   <div>
                <label for="email" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Email Address:</label>
                <input type="email" id="email" name="email" placeholder="e.g., yourname@example.com" required
                       class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
            </div>
    <div>
                <label for="phone" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Student's Phone Number:</label>
                <input type="tel" id="phone" name="phone" placeholder="e.g., +91-9876543210" required
                       class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
            </div>

  <div>
                <label for="address" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Full Residential Address:</label>
                <textarea id="address" name="address" rows="3" placeholder="House No., Street, Locality, City, State, Pincode" required
                          class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base resize-y transition duration-200 ease-in-out"></textarea>
            </div>

            <!-- Academic Information -->
         
         
  <div>
                <label for="lastQualification" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Highest Academic Qualification Completed:</label>
                <input type="text" id="lastQualification" name="lastQualification" placeholder="e.g., Class 10th Pass, Class 12th Pass" required
                       class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
            </div>
     <div>
                <label for="applyingClass" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Applying for Class:</label>
                <select id="applyingClass" name="applyingClass" required
                        class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
                    <option value="">Select Class</option>
                    <option value="1">Class 1st</option>
                    <option value="2">Class 2nd</option>
                    <option value="3">Class 3rd</option>
                    <option value="4">Class 4th</option>
                    <option value="5">Class 5th</option>
                    <option value="6">Class 6th</option>
                    <option value="7">Class 7th</option>
                    <option value="8">Class 8th</option>
                    <option value="9">Class 9th</option>
                    <option value="10">Class 10th</option>
                    <option value="11">Class 11th</option>
                    <option value="12">Class 12th</option>
                </select>
            </div>
     <div>
                <label for="courseOfInterest" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Desired Program/Course:</label>
                <select id="courseOfInterest" name="courseOfInterest" required
                        class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
                    <option value="">Select a Program</option>
                    <option value="JEE Main">JEE Main Preparation</option>
                    <option value="JEE Advanced">JEE Advanced Preparation</option>
                    <option value="NEET">NEET Preparation</option>
                    <option value="Foundation (1st-8th)">Foundation Program (Class 1st-8th)</option>
                    <option value="Foundation (9th-12th)">Foundation Program (Class 9th-12th)</option>
                    <option value="Other Competitive Exams">Other Competitive Exams Preparation</option>
                </select>
            </div>

            <!-- Parent/Guardian Information -->
   <div>
                <label for="parentName" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Parent/Guardian Full Name:</label>
                <input type="text" id="parentName" name="parentName" placeholder="e.g., Jane Doe" required
                       class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
            </div>
    <div>
                <label for="parentPhone" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">Parent/Guardian Phone Number:</label>
                <input type="tel" id="parentPhone" name="parentPhone" placeholder="e.g., +91-9876543210" required
                       class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
            </div>

            <!-- How did you hear about us? -->
          
<div>
                <label for="howHear" class="block text-sm sm:text-base font-semibold text-gray-700 mb-2">How did you hear about INFINITE STUDY?</label>
                <select id="howHear" name="howHear"
                        class="mt-1 block w-full px-4 py-2 sm:py-3 border border-gray-300 rounded-lg shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-base transition duration-200 ease-in-out">
                    <option value="">Select an Option</option>
                    <option value="Friends/Family">Friends/Family</option>
                    <option value="Social Media">Social Media</option>
                    <option value="Newspaper Ad">Newspaper Ad</option>
                    <option value="Website/Online Search">Website/Online Search</option>
                    <option value="Pamphlet/Flyer">Pamphlet/Flyer</option>
                    <option value="School Event">School Event</option>
                    <option value="Other">Other</option>
                </select>
            </div>

   <div class="text-center mt-8 pt-4">
                <button type="submit"
                        class="inline-flex items-center px-8 py-3 sm:py-4 border border-transparent text-base sm:text-lg font-medium rounded-xl shadow-md text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500 transition duration-300 ease-in-out transform hover:-translate-y-1 hover:scale-105">
                    Register Now
                </button>
            </div>
            <p class="text-xs sm:text-sm text-gray-500 text-center mt-6">
                @ All Copyright Reserved 2025 .
            </p>
        </form>
    </div>
</body>
</html>

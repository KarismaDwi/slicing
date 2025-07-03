<template>
       <div class="ml-48 max-w-2xl flex flex-col p-6">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">My Courses</h2>
            <div class="flex gap-4 mb-6"><span class="text-gray-600">Filter by:</span>
                <select class="border px-5 py-2 rounded-full text-sm">
                    <option>Time</option>
                </select>
                <select class="border px-5 py-2 rounded-full text-sm">
                    <option>Level</option>
                </select>
                <select class="border px-5 py-2 rounded-full text-sm">
                    <option>Language</option>
                </select>
                <select class="border px-5 py-2 rounded-full text-sm">
                    <option>Type</option>
                </select>
            </div>

            <div class="space-y-6">
                <div class="bg-white rounded-xl shadow p-6 flex justify-between items-center hover:bg-gray-100 transition-colors">
                    <div>
                        <h3 class="text-xl font-semibold">Operating System</h3>
                        <p class="text-sm text-gray-800">Learn the basic operating system: abstraction, mechanisms, and implementation.</p>
                        <p class="text-sm text-gray-800 mt-2">Created by <span class="text-purple-600 font-semibold">Mark Lee</span> </p>
                    </div>
                    <img src="https://i.pinimg.com/736x/df/da/99/dfda992fc75edcf9a462bc02057f24d5.jpg" alt="Course Image" class="w-20">
            </div>
                <div class="bg-purple-200 rounded-xl shadow p-6 flex justify-between items-center hover:bg-purple-100 transition-colors">
                    <div>
                        <h3 class="text-xl font-semibold">Aritificaal Intelligence</h3>
                        <p class="text-sm text-gray-800">Intelligence demonstrated by machines, unlike the natural intelligence displayed by humas and animals.</p>
                        <p class="text-sm text-gray-800 mt-2">Created by <span class="text-purple-600 font-semibold">Jung Jaehyun</span> </p>
                    </div>
                    <img src="https://i.pinimg.com/736x/df/da/99/dfda992fc75edcf9a462bc02057f24d5.jpg" alt="Course Image" class="w-20">
            </div>
                <div class="bg-pink-200 rounded-xl shadow p-6 flex justify-between items-center hover:bg-pink-100 transition-colors">
                    <div>
                        <h3 class="text-xl font-semibold">Software Engineering</h3>
                        <p class="text-sm text-gray-800">Learn detailed engineeringnof software design, development and maintenance.</p>
                        <p class="text-sm text-gray-800 mt-2">Created by <span class="text-purple-600 font-semibold">Windah Basudara </span> </p>
                    </div>
                    <img src="https://i.pinimg.com/736x/df/da/99/dfda992fc75edcf9a462bc02057f24d5.jpg" alt="Course Image" class="w-20">
            </div>
        </div>
    </div>
</template>
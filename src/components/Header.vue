<template>
    <div class="flex flex-shrink-0">
        <div class="w-64 flex-shrink-0 px-4 py-3 bg-gray-800">
            <button class="block w-full flex items-center">
                <img class="h-8 w-8 rounded-full object-cover" src="https://images.unsplash.com/photo-1614880353165-e56fac2ea9a8?ixid=MnwxMjA3fDB8MHxzZWFyY2h8OHx8cG9ydHJhaXQlMjB3b21hbnxlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=facearea&facepad=4&w=144&q=60" alt="avatar">
                <span class="ml-4 mr-2 text-sm font-medium text-white">Monica White</span>
                <svg class="ml-auto h-5 w-5 stroke-current text-gray-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="#000000" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <path d="M6 9l6 6 6-6"/>
                </svg>
            </button>
        </div>
        <div class="flex-1 flex bg-gray-700 px-6 items-center justify-between">
            <nav class="flex">
                <a
                href="#" 
                class=" px-3 py-2 leading-none rounded-lg bg-gray-800 text-sm text-white font-medium">
                Mailbox
                </a>
                <a
                href="#" 
                class=" ml-2 px-3 py-2 leading-none rounded-lg  text-sm text-white font-medium hover:bg-gray-600">
                Customers
                </a>
                <a
                href="#" 
                class=" ml-2 px-3 py-2 leading-none rounded-lg  text-sm text-white font-medium hover:bg-gray-600">
                Reporting
                </a>
                <a
                href="#" 
                class=" ml-2 px-3 py-2 leading-none rounded-lg  text-sm text-white font-medium hover:bg-gray-600">
                Manage
                </a>
            </nav>
            <div class="flex items-center">
                <span class="relative w-64">
                    <span class="absolute inset-y-0 left-0 flex items-center pl-2">
                    <svg class="stroke-current text-gray-400 h-5 w-5" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <circle cx="11" cy="11" r="8"></circle>
                        <line x1="21" y1="21" x2="16.65" y2="16.65"></line>
                    </svg>
                    </span>
                    <input 
                        class="block pl-9 pr-4 py-2 w-full bg-gray-900 rounded-lg text-sm placeholder-gray-400 text-white focus:bg-white focus:text-gray-900 focus:placeholder-gray-700 focus:outline-none"
                        placeholder="Search"
                    />
                </span>
                <button class="ml-5 text-gray-400 hover:text-gray-200">
                    <svg class="stroke-current w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9"></path>
                    </svg>
                </button>
                <button class="ml-4 text-gray-400 hover:text-gray-200">
                    <svg class="stroke-current h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.228 9c.549-1.165 2.03-2 3.772-2 2.21 0 4 1.343 4 3 0 1.4-1.278 2.575-3.006 2.907-.542.104-.994.54-.994 1.093m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                    </svg>
                </button>
            </div>
        </div>
    </div>
</template>
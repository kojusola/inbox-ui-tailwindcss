<template>
    <div class="w-64 p-6 bg-gray-100 overflow-y-auto">
        <nav>
            <h2 class="text-xs font-semibold text-gray-600 uppercase tracking-wider">Mailboxes</h2>
            <div class="mt-3">
                <a href="" class="mt-2 -mx-3 px-3 py-2 flex items-center justify-between text-sm font-medium bg-gray-200 rounded-lg">
                <span class="inline-flex">
                    <svg class="h-5 w-5 stroke-current text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 13V6a2 2 0 00-2-2H6a2 2 0 00-2 2v7m16 0v5a2 2 0 01-2 2H6a2 2 0 01-2-2v-5m16 0h-2.586a1 1 0 00-.707.293l-2.414 2.414a1 1 0 01-.707.293h-3.172a1 1 0 01-.707-.293l-2.414-2.414A1 1 0 006.586 13H4"></path>
                    </svg>
                    <span class="ml-2 text-gray-900">Inbox</span>
                </span>
                <span class=" inline-block w-9 text-center py-1 leading-none text-xs text-gray-700 font-semibold bg-gray-300 rounded-full">
                    6
                </span>
                </a>
                <a href="" class="mt-2 -mx-3 px-3 py-2 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
                <span class="inline-flex">
                    <svg class="h-5 w-5 stroke-current text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 21v-4m0 0V5a2 2 0 012-2h6.5l1 1H21l-3 6 3 6h-8.5l-1-1H5a2 2 0 00-2 2zm9-13.5V9"></path>
                    </svg>
                    <span class="ml-2 text-gray-700">Flagged</span>
                </span>
            </a>
            <a href="" class="mt-2 -mx-3 px-3 py-2 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
                <span class="inline-flex">
                    <svg  class="h-5 w-5 stroke-current text-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20 14.66V20a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h5.34">
                        </path><polygon points="18 2 22 6 12 16 8 16 8 12 18 2"></polygon>
                    </svg>
                    <span class="ml-2 text-gray-700">Drafts</span>
                </span>
                <span class=" inline-block w-9 text-center py-1 leading-none text-xs text-gray-700 font-semibold bg-gray-300 rounded-full">
                    2
                </span>
            </a>
            <a href="" class="mt-2 -mx-3 px-3 py-2 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
                <span class="inline-flex">
                    <svg class="h-5 w-5 stroke-current text-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <path d="M5.52 19c.64-2.2 1.84-3 3.22-3h6.52c1.38 0 2.58.8 3.22 3"/>
                        <circle cx="12" cy="10" r="3"/><circle cx="12" cy="12" r="10"/>
                    </svg>
                    <span class="ml-2 text-gray-700">Assigned</span>
                </span>
                <span class=" inline-block w-9 text-center py-1 leading-none text-xs text-gray-700 font-semibold bg-gray-300 rounded-full">
                    1
                </span>
            </a>
            <a href="" class="mt-2 -mx-3 px-3 py-2 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
                <span class="inline-flex">
                    <svg class="h-5 w-5 fill-current text-gray-500" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M12 2c5.514 0 10 4.486 10 10s-4.486 10-10 10-10-4.486-10-10 4.486-10 10-10zm0-2c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm4.393 7.5l-5.643 5.784-2.644-2.506-1.856 1.858 4.5 4.364 7.5-7.643-1.857-1.857z"/>
                        </svg>
                    <span class="ml-2 text-gray-700">Closed</span>
                </span>
            </a>
            <a href="" class="mt-2 -mx-3 px-3 py-2 flex items-center justify-between text-sm font-medium hover:bg-gray-200 rounded-lg">
                <span class="inline-flex">
                    <svg class="h-5 w-5 stroke-current text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 8h14M5 8a2 2 0 110-4h14a2 2 0 110 4M5 8v10a2 2 0 002 2h10a2 2 0 002-2V8m-9 4h4"></path>
                    </svg>
                    <span class="ml-2 text-gray-700">Junk</span>
                </span>
            </a>
            <div>
                <h2 class=" mt-8 text-xs font-semibold text-gray-600 uppercase tracking-wider">Folders</h2>
                <div class="mt-4">
                    <a href="#" class="block mt-4 text-sm font-medium text-gray-700">Refunds</a>
                    <a href="#" class="block mt-4 text-sm font-medium text-gray-700">Discounts</a>
                    <a href="#" class="block mt-4 text-sm font-medium text-gray-700">Bugs</a>
                </div>
            </div>
            </div>
        </nav>
    </div>
</template>
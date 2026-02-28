<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Qesone Financial Trust Bank</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .sidebar { transition: transform 0.3s ease-in-out; }
        .hidden { display: none; }
        @keyframes bounce-slow { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }
        .animate-bounce-slow { animation: bounce-slow 2s infinite; }
    </style>
</head>
<body class="bg-[#f4f7f9] font-sans">

    <div id="sidebar" class="sidebar fixed inset-y-0 left-0 w-72 bg-white shadow-2xl z-50 -translate-x-full">
        <div class="p-6 border-b bg-[#1a3a5f] text-white text-center">
            <div class="w-20 h-20 rounded-full bg-gray-200 mx-auto mb-2 overflow-hidden border-2 border-blue-400">
                <img src="https://ui-avatars.com/api/?name=Chris+Young&background=0D8ABC&color=fff" alt="Profile">
            </div>
            <h3 class="font-bold text-lg">Chris Young</h3>
            <p class="text-[10px] opacity-70">Online Banking Account</p>
        </div>
        <nav class="p-4 space-y-1">
            <a href="#" class="flex items-center p-3 text-blue-800 bg-blue-50 rounded-lg font-bold">🏠 Dashboard</a>
            <a href="#" class="flex items-center p-3 text-gray-600">👤 My Profile</a>
            <a href="#" class="flex items-center p-3 text-gray-600">💸 Transfer</a>
            <a href="#" class="flex items-center p-3 text-gray-600">📊 Transaction History</a>
            <a href="#" class="flex items-center p-3 text-gray-600">💳 My Credit Card</a>
            <a href="#" class="flex items-center p-3 text-red-600 mt-10 border-t pt-5">Logout</a>
        </nav>
    </div>

    <div class="max-w-md mx-auto min-h-screen pb-24 relative">
        <header class="bg-[#1a3a5f] p-4 flex justify-between items-center text-white sticky top-0 z-40 shadow-md">
            <button onclick="toggleSidebar()" class="text-2xl">☰</button>
            <div class="flex items-center gap-2">
                <div class="bg-white p-1 rounded italic text-[#1a3a5f] font-bold text-[10px]">Qesone</div>
                <span class="text-xs font-light">Financial Trust Bank</span>
            </div>
            <div class="w-8 h-8 rounded-full bg-blue-500 flex items-center justify-center text-xs font-bold shadow-inner">CY</div>
        </header>

        <main class="p-4 space-y-4">
            <div class="bg-white p-6 rounded-3xl shadow-sm text-center border border-gray-100">
                <div class="w-24 h-24 rounded-full mx-auto bg-gray-50 mb-3 border-4 border-white shadow-md flex items-center justify-center text-4xl">👤</div>
                <h1 class="text-xl font-black text-gray-800 tracking-tight">Welcome, Chris Young</h1>
            </div>

            <div class="space-y-3">
                <div class="bg-[#1a3a5f] text-white p-6 rounded-3xl relative overflow-hidden shadow-xl">
                    <p class="text-[10px] opacity-70 uppercase font-black tracking-widest">Available Balance</p>
                    <h2 class="text-2xl font-bold mt-1">USD $ 6,422,000.00</h2>
                    <div class="absolute top-4 right-4 w-5 h-5 rounded-full border-2 border-white/20 bg-white/5"></div>
                </div>
                <div class="bg-[#2a5a8f] text-white p-6 rounded-3xl relative overflow-hidden shadow-lg">
                    <p class="text-[10px] opacity-70 uppercase font-black tracking-widest">Cleared Balance</p>
                    <h2 class="text-2xl font-bold mt-1">USD $ 6,422,000.00</h2>
                    <div class="absolute top-4 right-4 w-5 h-5 rounded-full border-2 border-white/20 bg-white/5"></div>
                </div>
            </div>

            <div class="bg-white p-5 rounded-3xl shadow-sm border border-gray-100">
                <div class="flex justify-between items-center border-b border-gray-50 pb-3 mb-3">
                    <span class="text-gray-500 text-xs font-bold uppercase">Account Status</span>
                    <span class="bg-green-100 text-green-700 px-4 py-1 rounded-full text-[10px] font-black tracking-tighter">ACTIVE</span>
                </div>
                <div class="flex justify-between items-center text-sm">
                    <span class="text-gray-400">Account Number:</span>
                    <span class="font-bold text-gray-800">2109333236</span>
                </div>
            </div>

            <div class="bg-gradient-to-br from-blue-700 to-indigo-900 p-6 rounded-[2rem] shadow-2xl text-white relative">
                <div class="flex justify-between items-start mb-12">
                    <p class="italic font-black text-xl opacity-90">mastercard</p>
                    <div class="w-12 h-9 bg-yellow-400/80 rounded-lg shadow-inner"></div>
                </div>
                <p class="text-2xl tracking-[0.25em] font-mono mb-8 text-center">**** **** **** 3236</p>
                <div class="flex justify-between items-end">
                    <div class="uppercase text-[9px]">
                        <p class="opacity-60 mb-1">Card Holder</p>
                        <p class="font-bold text-sm">Chris Young</p>
                    </div>
                    <div class="uppercase text-[9px] text-right">
                        <p class="opacity-60 mb-1">Expires</p>
                        <p class="font-bold text-sm">05/28</p>
                    </div>
                </div>
            </div>

            <div class="pt-4">
                <div class="flex justify-between items-center mb-4 px-1">
                    <h3 class="text-gray-800 font-black text-lg">Recent Activity</h3>
                    <span class="text-blue-600 text-xs font-bold">View All</span>
                </div>
                <div class="space-y-3">
                    <div class="bg-white p-4 rounded-2xl shadow-sm flex justify-between items-center border-l-4 border-green-500">
                        <div>
                            <p class="text-[9px] text-gray-400 font-mono mb-1">TRX8829074017</p>
                            <p class="font-bold text-gray-800 text-sm">Investment Credit</p>
                            <p class="text-[10px] text-gray-400">2026-02-25 14:20</p>
                        </div>
                        <div class="text-right">
                            <p class="text-green-600 font-black">+$85,200.00</p>
                            <p class="text-[9px] text-green-500 font-bold italic">SUCCESSFUL</p>
                        </div>
                    </div>
                </div>
            </div>
        </main>
    </div>

    <div id="chat-bubble" onclick="toggleChat()" class="fixed bottom-6 right-6 w-14 h-14 bg-blue-600 rounded-full shadow-2xl flex items-center justify-center cursor-pointer z-50 border-2 border-white animate-bounce-slow">
        <span class="text-white text-2xl">💬</span>
    </div>

    <div id="chat-window" class="hidden fixed bottom-24 right-6 w-72 bg-white rounded-3xl shadow-2xl z-50 overflow-hidden border border-gray-100">
        <div class="bg-[#1a3a5f] p-4 text-white flex justify-between items-center">
            <div>
                <p class="font-bold text-sm">Qesone Support</p>
                <p class="text-[9px] opacity-70 italic">Online • Typically responds in 1m</p>
            </div>
            <button onclick="toggleChat()" class="text-xl">×</button>
        </div>
        <div class="p-4 h-64 bg-gray-50 overflow-y-auto text-xs space-y-3">
            <p class="bg-gray-200 p-3 rounded-2xl text-gray-700 w-3/4 shadow-sm">Hello Chris! How can we help you with your account 2109333236 today?</p>
        </div>
        <div class="p-3 border-t bg-white flex gap-2">
            <input type="text" placeholder="Type a message..." class="flex-1 text-xs p-2 border rounded-xl outline-none bg-gray-50">
            <button class="text-blue-600 font-bold text-xs pr-2">Send</button>
        </div>
    </div>

    <script>
        function toggleSidebar() { document.getElementById('sidebar').classList.toggle('-translate-x-full'); }
        function toggleChat() { document.getElementById('chat-window').classList.toggle('hidden'); }
    </script>
</body>
</html>

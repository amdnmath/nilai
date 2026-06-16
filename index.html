<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal Nilai Rapor - SMAN 5 PALU</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f3f4f6;
            margin: 0;
            padding: 0;
            -webkit-font-smoothing: antialiased;
        }

        /* Custom Animations */
        .fade-in {
            animation: fadeIn 0.4s ease-out forwards;
        }
        
        .slide-up {
            animation: slideUp 0.5s ease-out forwards;
            opacity: 0;
            transform: translateY(20px);
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .glass-effect {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
        }
        
        .hidden-view {
            display: none !important;
        }
    </style>
</head>
<body>

    <!-- Tampilan Pencarian (Search View) -->
    <div id="search-view" class="min-h-screen flex items-center justify-center p-4">
        <div class="max-w-md w-full space-y-8 glass-effect p-8 sm:p-10 rounded-3xl shadow-xl border border-gray-100 fade-in relative overflow-hidden">
            <!-- Decorative Background blob -->
            <div class="absolute -top-24 -right-24 w-48 h-48 bg-blue-100 rounded-full blur-3xl opacity-50 pointer-events-none"></div>
            <div class="absolute -bottom-24 -left-24 w-48 h-48 bg-purple-100 rounded-full blur-3xl opacity-50 pointer-events-none"></div>
            
            <div class="text-center relative z-10">
                <div class="mx-auto w-20 h-20 bg-blue-600 text-white rounded-2xl flex items-center justify-center shadow-lg transform rotate-3 hover:rotate-0 transition duration-300">
                    <i class="fa-solid fa-school text-3xl"></i>
                </div>
                <h2 class="mt-6 text-3xl font-extrabold text-gray-900 tracking-tight">Portal Nilai</h2>
                <p class="mt-2 text-sm text-gray-500 font-medium">SMAN 5 PALU • 11 MERDEKA 8</p>
                <p class="mt-1 text-xs text-gray-400">Tahun Pelajaran 2025/2026 Genap</p>
            </div>
            
            <form id="search-form" class="mt-8 space-y-6 relative z-10">
                <div class="rounded-md shadow-sm -space-y-px">
                    <div>
                        <label for="nisn" class="sr-only">Nomor Induk Siswa Nasional (NISN)</label>
                        <div class="relative">
                            <div class="absolute inset-y-0 left-0 pl-4 flex items-center pointer-events-none">
                                <i class="fa-solid fa-id-card text-gray-400"></i>
                            </div>
                            <input
                                id="nisn"
                                name="nisn"
                                type="text"
                                required
                                class="appearance-none rounded-xl relative block w-full px-4 py-4 pl-12 border border-gray-300 placeholder-gray-400 text-gray-900 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-blue-500 focus:z-10 sm:text-base transition-all bg-white/80 backdrop-blur-sm"
                                placeholder="Masukkan NISN Anda..."
                            />
                        </div>
                    </div>
                </div>

                <div id="error-message" class="hidden-view p-3 rounded-lg bg-red-50 border border-red-100 text-red-600 text-sm flex items-start animate-fade-in">
                    <i class="fa-solid fa-circle-exclamation mt-0.5 mr-2"></i>
                    <span id="error-text"></span>
                </div>

                <div>
                    <button
                        id="submit-btn"
                        type="submit"
                        class="group relative w-full flex justify-center py-4 px-4 border border-transparent text-sm font-semibold rounded-xl text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500 transition-all shadow-md hover:shadow-lg disabled:opacity-70"
                    >
                        <span id="btn-text" class="flex items-center">
                            Cari Data Rapor <i class="fa-solid fa-arrow-right ml-2 group-hover:translate-x-1 transition-transform"></i>
                        </span>
                        <span id="btn-loading" class="hidden-view flex items-center">
                            <i class="fa-solid fa-circle-notch fa-spin mr-2"></i> Memproses...
                        </span>
                    </button>
                </div>
            </form>

            <div class="mt-6 border-t border-gray-100 pt-6 relative z-10">
                <div class="bg-blue-50 rounded-lg p-4 flex gap-3 text-sm text-blue-800 items-start">
                    <i class="fa-solid fa-circle-info mt-0.5 text-blue-500"></i>
                    <p>Gunakan <strong>NISN</strong> (10 digit angka) sebagai kata kunci pencarian. Contoh NISN yang terdaftar: <span class="font-mono bg-blue-200 px-1 rounded">0096091003</span></p>
                </div>
            </div>
        </div>
    </div>

    <!-- Tampilan Hasil (Result View) -->
    <div id="result-view" class="min-h-screen py-8 px-4 sm:px-6 lg:px-8 hidden-view fade-in">
        <div class="max-w-4xl mx-auto space-y-6">
            
            <!-- Header Panel -->
            <div class="flex flex-col md:flex-row md:items-center justify-between glass-effect rounded-2xl shadow-sm border border-gray-200 p-6">
                <div class="flex items-center space-x-4 mb-4 md:mb-0">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center flex-shrink-0 text-blue-600">
                        <i class="fa-solid fa-user-graduate text-2xl"></i>
                    </div>
                    <div>
                        <h1 id="student-name" class="text-2xl font-bold text-gray-800 uppercase leading-tight">-</h1>
                        <p class="text-gray-500 font-medium">NISN: <span id="student-nisn">-</span> <span class="mx-2">•</span> NIS: <span id="student-nis">-</span></p>
                    </div>
                </div>
                <button 
                    id="back-btn"
                    class="inline-flex items-center justify-center px-4 py-2 border border-transparent text-sm font-medium rounded-lg text-white bg-gray-800 hover:bg-gray-700 transition shadow-sm"
                >
                    <i class="fa-solid fa-arrow-left mr-2"></i> Cari Lainnya
                </button>
            </div>

            <!-- Info Cards -->
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 slide-up" style="animation-delay: 0.1s;">
                <div class="bg-white rounded-2xl p-6 shadow-sm border border-gray-100 flex items-center space-x-4">
                    <div class="w-12 h-12 bg-green-100 text-green-600 rounded-xl flex items-center justify-center text-xl">
                        <i class="fa-solid fa-trophy"></i>
                    </div>
                    <div>
                        <p class="text-sm text-gray-500 font-medium">Peringkat Kelas</p>
                        <p class="text-2xl font-bold text-gray-800"><span id="student-rank">-</span> <span class="text-sm font-normal text-gray-400">/ 32</span></p>
                    </div>
                </div>
                <div class="bg-white rounded-2xl p-6 shadow-sm border border-gray-100 flex items-center space-x-4">
                    <div class="w-12 h-12 bg-blue-100 text-blue-600 rounded-xl flex items-center justify-center text-xl">
                        <i class="fa-solid fa-chart-line"></i>
                    </div>
                    <div>
                        <p class="text-sm text-gray-500 font-medium">Rata-rata Nilai</p>
                        <p id="student-average" class="text-2xl font-bold text-gray-800">-</p>
                    </div>
                </div>
                <div class="bg-white rounded-2xl p-6 shadow-sm border border-gray-100 flex items-center space-x-4">
                    <div class="w-12 h-12 bg-purple-100 text-purple-600 rounded-xl flex items-center justify-center text-xl">
                        <i class="fa-solid fa-calculator"></i>
                    </div>
                    <div>
                        <p class="text-sm text-gray-500 font-medium">Total Nilai</p>
                        <p id="student-total" class="text-2xl font-bold text-gray-800">-</p>
                    </div>
                </div>
            </div>

            <!-- Table Panel -->
            <div class="bg-white rounded-2xl shadow-sm border border-gray-100 overflow-hidden slide-up" style="animation-delay: 0.2s;">
                <div class="px-6 py-5 border-b border-gray-100 bg-gray-50/50 flex justify-between items-center">
                    <h3 class="text-lg leading-6 font-semibold text-gray-800">
                        <i class="fa-solid fa-list-check mr-2 text-blue-500"></i> Detail Nilai Mata Pelajaran
                    </h3>
                </div>
                <div class="overflow-x-auto">
                    <table class="min-w-full divide-y divide-gray-200">
                        <thead class="bg-gray-50">
                            <tr>
                                <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider w-16">No</th>
                                <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Mata Pelajaran</th>
                                <th scope="col" class="px-6 py-3 text-center text-xs font-medium text-gray-500 uppercase tracking-wider">Nilai Akhir</th>
                                <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Predikat</th>
                            </tr>
                        </thead>
                        <tbody id="scores-tbody" class="bg-white divide-y divide-gray-200">
                            <!-- Table rows will be inserted here dynamically -->
                        </tbody>
                    </table>
                </div>
            </div>
            
            <div class="text-center mt-8 text-gray-400 text-sm pb-8">
                &copy; 2026 SMAN 5 PALU - Kelas 11 MERDEKA 8
            </div>
        </div>
    </div>

    <script>
        const studentData = [
            { nisn: "0096091003", nis: "094129145", name: "Muh. Rifkhy Ramadhan R. Hambali", scores: { "Pendidikan Agama": 92, "Pendidikan Pancasila": 95, "Bahasa Indonesia": 85, "Bahasa Inggris": 87, "Matematika Umum": 91, "PJOK": 90, "Sejarah": 95, "Fisika": 90, "Kimia": 97, "Ekonomi": 88, "Geografi": 93, "Informatika": 90 }, total: 1093, average: 91.1, rank: 1 },
            { nisn: "0095839861", nis: "094129199", name: "REA AULIA", scores: { "Pendidikan Agama": 90, "Pendidikan Pancasila": 90, "Bahasa Indonesia": 87, "Bahasa Inggris": 87, "Matematika Umum": 91, "PJOK": 95, "Sejarah": 90, "Fisika": 85, "Kimia": 96, "Ekonomi": 91, "Geografi": 92, "Informatika": 90 }, total: 1084, average: 90.3, rank: 2 },
            { nisn: "0095335629", nis: "094129247", name: "ULYARTA N. SIMANJUNTAK", scores: { "Pendidikan Agama": 92, "Pendidikan Pancasila": 92, "Bahasa Indonesia": 88, "Bahasa Inggris": 86, "Matematika Umum": 82, "PJOK": 90, "Sejarah": 93, "Fisika": 85, "Kimia": 96, "Ekonomi": 90, "Geografi": 90, "Informatika": 90 }, total: 1074, average: 89.5, rank: 3 },
            { nisn: "0095336123", nis: "094129108", name: "Maulydia Natasya", scores: { "Pendidikan Agama": 90, "Pendidikan Pancasila": 90, "Bahasa Indonesia": 85, "Bahasa Inggris": 84, "Matematika Umum": 90, "PJOK": 90, "Sejarah": 95, "Fisika": 90, "Kimia": 94, "Ekonomi": 91, "Geografi": 91, "Informatika": 82 }, total: 1072, average: 89.3, rank: 4 },
            { nisn: "3084695918", nis: "094129330", name: "Fakhri Mukhtar", scores: { "Pendidikan Agama": 90, "Pendidikan Pancasila": 90, "Bahasa Indonesia": 88, "Bahasa Inggris": 87, "Matematika Umum": 81, "PJOK": 95, "Sejarah": 89, "Fisika": 85, "Kimia": 96, "Ekonomi": 90, "Geografi": 90, "Informatika": 90 }, total: 1071, average: 89.3, rank: 5 },
            { nisn: "0092613557", nis: "094129146", name: "Muh. Salman Alfarisyi", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 85, "Bahasa Indonesia": 82, "Bahasa Inggris": 86, "Matematika Umum": 91, "PJOK": 90, "Sejarah": 95, "Fisika": 90, "Kimia": 97, "Ekonomi": 90, "Geografi": 88, "Informatika": 90 }, total: 1069, average: 89.1, rank: 6 },
            { nisn: "0099697535", nis: "094129067", name: "Febrian Aditya", scores: { "Pendidikan Agama": 90, "Pendidikan Pancasila": 80, "Bahasa Indonesia": 86, "Bahasa Inggris": 86, "Matematika Umum": 85, "PJOK": 90, "Sejarah": 85, "Fisika": 90, "Kimia": 96, "Ekonomi": 89, "Geografi": 92, "Informatika": 90 }, total: 1059, average: 88.3, rank: 7 },
            { nisn: "0099139052", nis: "094129222", name: "Salwan ya'u", scores: { "Pendidikan Agama": 92, "Pendidikan Pancasila": 90, "Bahasa Indonesia": 87, "Bahasa Inggris": 84, "Matematika Umum": 91, "PJOK": 80, "Sejarah": 90, "Fisika": 85, "Kimia": 90, "Ekonomi": 90, "Geografi": 90, "Informatika": 90 }, total: 1059, average: 88.3, rank: 7 },
            { nisn: "0095030286", nis: "094128996", name: "Alisya Rahmadani", scores: { "Pendidikan Agama": 90, "Pendidikan Pancasila": 90, "Bahasa Indonesia": 88, "Bahasa Inggris": 84, "Matematika Umum": 81, "PJOK": 90, "Sejarah": 85, "Fisika": 85, "Kimia": 95, "Ekonomi": 90, "Geografi": 88, "Informatika": 90 }, total: 1056, average: 88.0, rank: 9 },
            { nisn: "0097944148", nis: "094129095", name: "Jessica Revalina Nurtanio", scores: { "Pendidikan Agama": 92, "Pendidikan Pancasila": 85, "Bahasa Indonesia": 88, "Bahasa Inggris": 78, "Matematika Umum": 82, "PJOK": 90, "Sejarah": 95, "Fisika": 85, "Kimia": 88, "Ekonomi": 90, "Geografi": 88, "Informatika": 90 }, total: 1051, average: 87.6, rank: 10 },
            { nisn: "0082108520", nis: "094129241", name: "Syifia Ramadhani", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 85, "Bahasa Indonesia": 85, "Bahasa Inggris": 80, "Matematika Umum": 82, "PJOK": 90, "Sejarah": 94, "Fisika": 85, "Kimia": 90, "Ekonomi": 90, "Geografi": 90, "Informatika": 90 }, total: 1046, average: 87.2, rank: 11 },
            { nisn: "0094658247", nis: "094128992", name: "ALIA APRILIA", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 80, "Bahasa Indonesia": 87, "Bahasa Inggris": 76, "Matematika Umum": 82, "PJOK": 90, "Sejarah": 93, "Fisika": 85, "Kimia": 88, "Ekonomi": 90, "Geografi": 90, "Informatika": 90 }, total: 1036, average: 86.3, rank: 12 },
            { nisn: "0099725665", nis: "094129024", name: "Ashraffil Syaban", scores: { "Pendidikan Agama": 90, "Pendidikan Pancasila": 78, "Bahasa Indonesia": 87, "Bahasa Inggris": 83, "Matematika Umum": 91, "PJOK": 85, "Sejarah": 86, "Fisika": 80, "Kimia": 85, "Ekonomi": 89, "Geografi": 85, "Informatika": 90 }, total: 1029, average: 85.8, rank: 13 },
            { nisn: "0094343254", nis: "094129037", name: "AZIRA", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 80, "Bahasa Indonesia": 86, "Bahasa Inggris": 81, "Matematika Umum": 79, "PJOK": 95, "Sejarah": 90, "Fisika": 80, "Kimia": 88, "Ekonomi": 90, "Geografi": 85, "Informatika": 90 }, total: 1029, average: 85.8, rank: 13 },
            { nisn: "0094481792", nis: "094129012", name: "Anita Septiana", scores: { "Pendidikan Agama": 80, "Pendidikan Pancasila": 86, "Bahasa Indonesia": 85, "Bahasa Inggris": 75, "Matematika Umum": 83, "PJOK": 90, "Sejarah": 92, "Fisika": 80, "Kimia": 88, "Ekonomi": 90, "Geografi": 85, "Informatika": 90 }, total: 1024, average: 85.3, rank: 15 },
            { nisn: "0087765946", nis: "094129308", name: "RAHMAT ADITYA", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 78, "Bahasa Indonesia": 84, "Bahasa Inggris": 84, "Matematika Umum": 81, "PJOK": 78, "Sejarah": 86, "Fisika": 85, "Kimia": 90, "Ekonomi": 91, "Geografi": 90, "Informatika": 90 }, total: 1022, average: 85.2, rank: 16 },
            { nisn: "0094278552", nis: "094129303", name: "NUR RAHMAWATI", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 80, "Bahasa Indonesia": 84, "Bahasa Inggris": 75, "Matematika Umum": 79, "PJOK": 94, "Sejarah": 87, "Fisika": 80, "Kimia": 88, "Ekonomi": 90, "Geografi": 85, "Informatika": 85 }, total: 1012, average: 84.3, rank: 17 },
            { nisn: "0089342009", nis: "094129697", name: "INDA RAHMA", scores: { "Pendidikan Agama": 87, "Pendidikan Pancasila": 85, "Bahasa Indonesia": 83, "Bahasa Inggris": 82, "Matematika Umum": 80, "PJOK": 85, "Sejarah": 85, "Fisika": 87, "Kimia": 90, "Ekonomi": 88, "Geografi": 78, "Informatika": 80 }, total: 1010, average: 84.2, rank: 18 },
            { nisn: "0092358153", nis: "094129116", name: "MOH YUGA PERMANA PUTRA", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 80, "Bahasa Indonesia": 82, "Bahasa Inggris": 75, "Matematika Umum": 79, "PJOK": 85, "Sejarah": 87, "Fisika": 80, "Kimia": 90, "Ekonomi": 89, "Geografi": 87, "Informatika": 90 }, total: 1009, average: 84.1, rank: 19 },
            { nisn: "0095378535", nis: "094129224", name: "SARAH", scores: { "Pendidikan Agama": 87, "Pendidikan Pancasila": 70, "Bahasa Indonesia": 82, "Bahasa Inggris": 85, "Matematika Umum": 79, "PJOK": 80, "Sejarah": 85, "Fisika": 85, "Kimia": 88, "Ekonomi": 90, "Geografi": 83, "Informatika": 90 }, total: 1004, average: 83.7, rank: 20 },
            { nisn: "0095336743", nis: "094128988", name: "Aisya Khumairah Siruah", scores: { "Pendidikan Agama": 78, "Pendidikan Pancasila": 80, "Bahasa Indonesia": 81, "Bahasa Inggris": 88, "Matematika Umum": 80, "PJOK": 83, "Sejarah": 85, "Fisika": 85, "Kimia": 88, "Ekonomi": 90, "Geografi": 80, "Informatika": 85 }, total: 1003, average: 83.6, rank: 21 },
            { nisn: "0096065142", nis: "094129176", name: "NUR FADHILAH", scores: { "Pendidikan Agama": 90, "Pendidikan Pancasila": 90, "Bahasa Indonesia": 84, "Bahasa Inggris": 75, "Matematika Umum": 79, "PJOK": 91, "Sejarah": 87, "Fisika": 70, "Kimia": 82, "Ekonomi": 90, "Geografi": 85, "Informatika": 80 }, total: 1003, average: 83.6, rank: 21 },
            { nisn: "0082754633", nis: "094129267", name: "AHMAD KHALIQ", scores: { "Pendidikan Agama": 90, "Pendidikan Pancasila": 75, "Bahasa Indonesia": 83, "Bahasa Inggris": 76, "Matematika Umum": 82, "PJOK": 75, "Sejarah": 88, "Fisika": 80, "Kimia": 85, "Ekonomi": 89, "Geografi": 82, "Informatika": 90 }, total: 995, average: 82.9, rank: 23 },
            { nisn: "0096276990", nis: "094129094", name: "Jesika", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 75, "Bahasa Indonesia": 84, "Bahasa Inggris": 75, "Matematika Umum": 80, "PJOK": 87, "Sejarah": 85, "Fisika": 80, "Kimia": 80, "Ekonomi": 90, "Geografi": 86, "Informatika": 87 }, total: 994, average: 82.8, rank: 24 },
            { nisn: "0097208060", nis: "094129068", name: "Febrian Valentino", scores: { "Pendidikan Agama": 80, "Pendidikan Pancasila": 78, "Bahasa Indonesia": 85, "Bahasa Inggris": 76, "Matematika Umum": 79, "PJOK": 90, "Sejarah": 80, "Fisika": 70, "Kimia": 88, "Ekonomi": 89, "Geografi": 90, "Informatika": 85 }, total: 990, average: 82.5, rank: 25 },
            { nisn: "0094507278", nis: "094129168", name: "Nesya Yunita Putri", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 80, "Bahasa Indonesia": 84, "Bahasa Inggris": 75, "Matematika Umum": 80, "PJOK": 85, "Sejarah": 89, "Fisika": 70, "Kimia": 80, "Ekonomi": 90, "Geografi": 84, "Informatika": 80 }, total: 982, average: 81.8, rank: 26 },
            { nisn: "0091719314", nis: "094129647", name: "DANIEL FERDINAN MUMU", scores: { "Pendidikan Agama": 75, "Pendidikan Pancasila": 75, "Bahasa Indonesia": 80, "Bahasa Inggris": 70, "Matematika Umum": 79, "PJOK": 80, "Sejarah": 86, "Fisika": 70, "Kimia": 80, "Ekonomi": 89, "Geografi": 80, "Informatika": 87 }, total: 951, average: 79.3, rank: 27 },
            { nisn: "3084136533", nis: "094129178", name: "NURADZIZ MJ. HUSAINI", scores: { "Pendidikan Agama": 85, "Pendidikan Pancasila": 75, "Bahasa Indonesia": 50, "Bahasa Inggris": 76, "Matematika Umum": 79, "PJOK": 75, "Sejarah": 85, "Fisika": 80, "Kimia": 85, "Ekonomi": 89, "Geografi": 78, "Informatika": 90 }, total: 947, average: 78.9, rank: 28 },
            { nisn: "0086258833", nis: "094129137", name: "MOHAMMAD FAREL ABDILAH", scores: { "Pendidikan Agama": 80, "Pendidikan Pancasila": 75, "Bahasa Indonesia": 88, "Bahasa Inggris": 70, "Matematika Umum": 79, "PJOK": 86, "Sejarah": 50, "Fisika": 70, "Kimia": 85, "Ekonomi": 88, "Geografi": 78, "Informatika": 88 }, total: 937, average: 78.1, rank: 29 },
            { nisn: "0094137331", nis: "094129184", name: "Prayer Rivaevel Bhayangkara", scores: { "Pendidikan Agama": 73, "Pendidikan Pancasila": 40, "Bahasa Indonesia": 40, "Bahasa Inggris": 82, "Matematika Umum": 81, "PJOK": 90, "Sejarah": 78, "Fisika": 80, "Kimia": 86, "Ekonomi": 89, "Geografi": 90, "Informatika": 80 }, total: 909, average: 75.8, rank: 30 },
            { nisn: "0105414253", nis: "094129126", name: "MOH. FIQRAN", scores: { "Pendidikan Agama": 80, "Pendidikan Pancasila": 50, "Bahasa Indonesia": 40, "Bahasa Inggris": 75, "Matematika Umum": 77, "PJOK": 85, "Sejarah": 85, "Fisika": 80, "Kimia": 88, "Ekonomi": 87, "Geografi": 80, "Informatika": 80 }, total: 907, average: 75.6, rank: 31 },
            { nisn: "0092654386", nis: "094129343", name: "ANDRIANSYA", scores: { "Pendidikan Agama": 0, "Pendidikan Pancasila": 0, "Bahasa Indonesia": 0, "Bahasa Inggris": 0, "Matematika Umum": 0, "PJOK": 0, "Sejarah": 0, "Fisika": 0, "Kimia": 0, "Ekonomi": 0, "Geografi": 0, "Informatika": 0 }, total: 0, average: 0, rank: 32 }
        ];

        const getPredikat = (score) => {
            if(score === 0) return "-";
            if(score >= 90) return "A (Sangat Baik)";
            if(score >= 80) return "B (Baik)";
            if(score >= 70) return "C (Cukup)";
            return "D (Kurang)";
        };

        const getPredikatColor = (score) => {
            if(score === 0) return "text-gray-400";
            if(score >= 90) return "text-green-600 font-semibold";
            if(score >= 80) return "text-blue-600 font-semibold";
            if(score >= 70) return "text-yellow-600 font-semibold";
            return "text-red-600 font-semibold";
        };

        // DOM Elements
        const searchForm = document.getElementById('search-form');
        const nisnInput = document.getElementById('nisn');
        const errorContainer = document.getElementById('error-message');
        const errorText = document.getElementById('error-text');
        const btnText = document.getElementById('btn-text');
        const btnLoading = document.getElementById('btn-loading');
        const submitBtn = document.getElementById('submit-btn');
        const searchView = document.getElementById('search-view');
        const resultView = document.getElementById('result-view');
        const backBtn = document.getElementById('back-btn');

        // Render functions
        const renderResult = (student) => {
            document.getElementById('student-name').textContent = student.name;
            document.getElementById('student-nisn').textContent = student.nisn;
            document.getElementById('student-nis').textContent = student.nis;
            document.getElementById('student-rank').textContent = student.rank;
            document.getElementById('student-average').textContent = student.average;
            document.getElementById('student-total').textContent = student.total;

            const tbody = document.getElementById('scores-tbody');
            tbody.innerHTML = ''; // Clear previous

            let index = 1;
            for (const [subject, score] of Object.entries(student.scores)) {
                const tr = document.createElement('tr');
                tr.className = 'hover:bg-blue-50/50 transition-colors';
                
                tr.innerHTML = `
                    <td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">${index}</td>
                    <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-800">${subject}</td>
                    <td class="px-6 py-4 whitespace-nowrap text-sm text-center font-bold text-gray-900 bg-gray-50/50">${score}</td>
                    <td class="px-6 py-4 whitespace-nowrap text-sm ${getPredikatColor(score)}">
                        ${getPredikat(score)}
                    </td>
                `;
                tbody.appendChild(tr);
                index++;
            }

            // Switch views
            searchView.classList.add('hidden-view');
            resultView.classList.remove('hidden-view');
        };

        // Event Listeners
        searchForm.addEventListener('submit', (e) => {
            e.preventDefault();
            
            // Hide error initially
            errorContainer.classList.add('hidden-view');
            
            const nisn = nisnInput.value.trim();
            if (!nisn) {
                errorText.textContent = 'Silakan masukkan NISN terlebih dahulu.';
                errorContainer.classList.remove('hidden-view');
                return;
            }

            // Loading state
            btnText.classList.add('hidden-view');
            btnLoading.classList.remove('hidden-view');
            submitBtn.disabled = true;

            // Simulate slight delay
            setTimeout(() => {
                const student = studentData.find(s => s.nisn === nisn);
                
                if (student) {
                    renderResult(student);
                } else {
                    errorText.textContent = 'Data siswa tidak ditemukan. Periksa kembali NISN Anda.';
                    errorContainer.classList.remove('hidden-view');
                }

                // Reset loading state
                btnText.classList.remove('hidden-view');
                btnLoading.classList.add('hidden-view');
                submitBtn.disabled = false;
            }, 500);
        });

        backBtn.addEventListener('click', () => {
            nisnInput.value = '';
            errorContainer.classList.add('hidden-view');
            
            // Switch views back
            resultView.classList.add('hidden-view');
            searchView.classList.remove('hidden-view');
        });

    </script>
</body>
</html>
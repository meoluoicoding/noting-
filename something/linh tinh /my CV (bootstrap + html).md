---
type: Page
title: my CV (bootstrap + html)
description: null
icon: 😄
createdAt: '2024-11-09T06:17:17.417Z'
creationDate: 2024-11-09 13:17
modificationDate: 2024-11-09 17:23
tags: []
coverImage: null
---

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>
    <!-- Bootstrap CSS -->
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* General Styles */
        body {
            background-image: url('https://images.unsplash.com/photo-1506748686214-9ac83d39fa7f?crop=entropy&cs=tinysrgb&fit=max&ixid=MnwzNjUyOXwwfDF8c2VhY2h8MXx8c2VhdHVyYWwlMjBmb3Jlc3R8ZW58MHx8fHwxNjg2Njg5MTg0&ixlib=rb-1.2.1&q=80&w=1080');
            background-size: cover;
            background-position: center;
            font-family: sans-serif;
            transition: background-color 0.3s, color 0.3s;
        }

        .header {
            background: linear-gradient(to right, rgba(126, 34, 206, 0.8), rgba(236, 72, 153, 0.8), rgba(220, 38, 38, 0.8));
            color: white;
            border-radius: 0.5rem;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            padding: 2rem;
        }

        .img-container img {
            width: 6rem;
            height: 6rem;
            max-width: 6rem;
            max-height: 6rem;
            border-radius: 50%;
            border: 4px solid white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-right: 1.5rem;
        }

        .title-container {
            position: relative;
            overflow: hidden;
        }

        .title-container h1 {
            font-size: 2.5rem;
            font-weight: 800;
        }

        .title-container h2 {
            font-size: 1.25rem;
            font-style: italic;
            color: #fde68a;
            margin-top: 0.5rem;
            white-space: nowrap;
            display: inline-block;
            animation: scrollText 6s linear infinite;
        }

        /* Keyframes to create the scrolling effect */
        @keyframes scrollText {
            0% {
                transform: translateX(100%);
            }
            50% {
                transform: translateX(0);
            }
            100% {
                transform: translateX(-100%);
            }
        }

        /* Dark Mode Styles */
        .dark-mode {
            background-color: #282a36;
            color: #f8f8f2;
        }

        .dark-mode .header {
            background: linear-gradient(to right, #44475a, #6272a4);
        }

        /* Override text color in these sections for dark mode */
        .dark-mode .card.bg-light .card-body,
        .dark-mode .list-group-item {
            color: black;
            background-color: #f8f9fa;
        }

        /* Progress Bar Styles */
        .progress {
            height: 1.5rem;
            margin-bottom: 1rem;
            border-radius: 0.5rem;
            overflow: hidden;
        }

        .progress-bar {
            font-size: 0.875rem;
            line-height: 1.5rem;
            text-align: center;
        }
    </style>
</head>
<body>

<!-- Dark Mode Toggle Button -->
<div class="container mt-3 text-right">
    <button id="toggleDarkMode" class="btn btn-secondary">Toggle Dark Mode</button>
</div>

<!-- Language Toggle Button -->
<div class="container mt-3 text-right">
    <button id="toggleLanguage" class="btn btn-secondary">Switch to Japanese</button>
</div>

<!-- Header Section -->
<header class="header d-flex align-items-center mb-4">
    <div class="img-container">
        <img src="assets/461519639_1054398469492021_1252424130496335956_n.jpg" alt="Profile Picture" />
    </div>
    <div class="title-container" style="width: calc(100% - 8rem);">
        <h1 data-en="Trần Anh Khoa" data-jp="トランアンクオア"></h1>
        <h2 data-en="English + Japanese Translator" data-jp="英日翻訳家"></h2>
    </div>
</header>

<!-- Main Content Section -->
<div class="container">
    <div class="row">
        <!-- Sidebar (Contact, Skills, Certificates) -->
        <aside class="col-md-4 mb-4">
            <!-- Contact Section -->
            <div class="card bg-light mb-4">
                <div class="card-body">
                    <h5 class="card-title text-primary"><i class="fas fa-phone-alt"></i> Contact</h5>
                    <ul class="list-unstyled">
                        <li><a href="https://www.facebook.com/profile.php?id=100047656324869" class="text-decoration-none text-info"><i class="fab fa-facebook-square"></i> Facebook Profile</a></li>
                        <li><a href="https://voz.vn/u/meoluoitt1.1949097/" class="text-decoration-none text-info"><i class="fab fa-vk"></i> Voz Profile</a></li>
                    </ul>
                </div>
            </div>

            <!-- Skills Section -->
            <div class="card bg-light mb-4">
                <div class="card-body">
                    <h5 class="card-title text-primary"><i class="fas fa-cogs"></i> Skills</h5>
                    <div class="mb-3">
                        <h6 data-en="English" data-jp="英語" class="text-success"></h6>
                        <div class="progress">
                            <div class="progress-bar bg-success" role="progressbar" style="width: 80%;" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"><span data-en="80%" data-jp="80％">80%</span></div>
                        </div>
                    </div>
                    <div class="mb-3">
                        <h6 data-en="Korean" data-jp="韓国語" class="text-warning"></h6>
                        <div class="progress">
                            <div class="progress-bar bg-warning" role="progressbar" style="width: 50%;" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100"><span data-en="50%" data-jp="50％">50%</span></div>
                        </div>
                    </div>
                    <div class="mb-3">
                        <h6 data-en="Japanese" data-jp="日本語" class="text-danger"></h6>
                        <div class="progress">
                            <div class="progress-bar bg-danger" role="progressbar" style="width: 80%;" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100"><span data-en="80%" data-jp="80％">80%</span></div>
                        </div>
                    </div>
                    <div class="mb-3">
                        <h6 data-en="Chinese" data-jp="中国語" class="text-info"></h6>
                        <div class="progress">
                            <div class="progress-bar bg-info" role="progressbar" style="width: 30%;" aria-valuenow="30" aria-valuemin="0" aria-valuemax="100"><span data-en="30%" data-jp="30％">30%</span></div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Certificates Section -->
            <div class="card bg-light">
                <div class="card-body">
                    <h5 class="card-title text-primary"><i class="fas fa-certificate"></i> Certificates</h5>
                    <ul class="list-group">
                        <li class="list-group-item d-flex justify-content-between align-items-center">
                            <span data-en="N2" data-jp="N2">N2</span>
                            <span class="badge badge-success badge-pill">Advanced</span>
                        </li>
                        <li class="list-group-item d-flex justify-content-between align-items-center">
                            <span data-en="University Degree" data-jp="大学卒業">University Degree</span>
                            <span class="badge badge-info badge-pill">Graduate</span>
                        </li>
                        <li class="list-group-item d-flex justify-content-between align-items-center">
                            <span data-en="Master’s Degree" data-jp="修士号">Master’s Degree</span>
                            <span class="badge badge-warning badge-pill">Postgraduate</span>
                        </li>
                    </ul>
                </div>
            </div>
        </aside>

        <!-- Main Profile Content -->
        <main class="col-md-8">
            <!-- Introduction Section -->
            <section class="mb-3">
                <button class="btn btn-primary w-100 text-left dropdown-button" type="button" data-toggle="collapse" data-target="#introductionSection" aria-expanded="false" aria-controls="introductionSection">
                    <i class="fas fa-user"></i> <span data-en="Introduction" data-jp="自己紹介">Introduction</span>
                </button>
                <div id="introductionSection" class="collapse mt-2">
                    <p class="text-muted" data-en="Hello everyone, my name's Khoa. I love learning languages, reading books, playing games, and playing billiards." data-jp="皆さんこんにちは、私の名前はクアです。言語学習、読書、ゲーム、ビリヤードが好きです。"></p>
                </div>
            </section>

            <!-- Professional Skills Section -->
            <section class="mb-3">
                <button class="btn btn-primary w-100 text-left dropdown-button" type="button" data-toggle="collapse" data-target="#professionalSkillsSection" aria-expanded="false" aria-controls="professionalSkillsSection">
                    <i class="fas fa-briefcase"></i> <span data-en="Professional Skills" data-jp="専門的なスキル">Professional Skills</span>
                </button>
                <div id="professionalSkillsSection" class="collapse mt-2">
                    <div class="mb-4">
                        <h3 class="h5 text-success" data-en="Language Translation" data-jp="言語翻訳">Language Translation</h3>
                        <p data-en="Experienced in translating business documents and files, ensuring accuracy and clarity." data-jp="ビジネス文書やファイルの翻訳において、正確さと明確さを確保する経験があります。"></p>
                    </div>
                    <div class="mb-4">
                        <h3 class="h5 text-warning" data-en="Computer Skills" data-jp="コンピューターのスキル">Computer Skills</h3>
                        <p data-en="Proficient in Microsoft Office Suite, Canva, and other productivity applications." data-jp="Microsoft Office Suite、Canva、その他の生産性アプリケーションに精通しています。"></p>
                    </div>
                    <div class="mb-4">
                        <h3 class="h5 text-danger" data-en="Research & AI Learning" data-jp="研究とAI学習">Research & AI Learning</h3>
                        <p data-en="Skilled in using ChatGPT, other AI tools, and conducting online research for continuous self-improvement." data-jp="ChatGPTやその他のAIツールを使用したり、オンラインでの研究を行うことにより、持続的な自己改善を図っています。"></p>
                    </div>
                </div>
            </section>

            <!-- Internship Section -->
            <section class="mb-3">
                <button class="btn btn-info w-100 text-left dropdown-button" type="button" data-toggle="collapse" data-target="#internshipSection" aria-expanded="false" aria-controls="internshipSection">
                    <i class="fas fa-briefcase"></i> <span data-en="Internship at Thanh Cong Company (2022 - 2024)" data-jp="Thanh Cong社でのインターンシップ（2022年 - 2024年）">Internship at Thanh Cong Company (2022 - 2024)</span>
                </button>
                <div id="internshipSection" class="collapse mt-2">
                    <p class="text-muted" data-en="Completed a two-year internship focused on English to Vietnamese translation in the manufacturing sector. Gained experience in technical documentation and effective communication within a corporate environment." data-jp="製造業での英語からベトナム語への翻訳を中心とした2年間のインターンシップを修了しました。技術文書の作成と企業環境での効果的なコミュニケーションにおける経験を積みました。"></p>
                </div>
            </section>

            <!-- Additional sections as needed -->
        </main>
    </div>
</div>

<!-- Bootstrap JS (necessary for some Bootstrap components) -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>

<script>
    // Dark Mode Toggle Script with Persistence
    const toggleButton = document.getElementById('toggleDarkMode');
    const body = document.body;
    const darkModeKey = 'darkModeEnabled';

    // Check if dark mode is enabled in localStorage
    const isDarkMode = localStorage.getItem(darkModeKey) === 'true';
    if (isDarkMode) {
        body.classList.add('dark-mode');
    }

    // Toggle dark mode and save preference to localStorage
    toggleButton.addEventListener('click', () => {
        body.classList.toggle('dark-mode');
        const darkModeEnabled = body.classList.contains('dark-mode');
        localStorage.setItem(darkModeKey, darkModeEnabled);
    });

    // Language Toggle Script
    const toggleLanguageButton = document.getElementById('toggleLanguage');
    const japaneseVersionKey = 'japaneseVersionEnabled';

    // Function to switch between English and Japanese versions
    const toggleLanguage = () => {
        const isJapaneseVersion = body.classList.contains('japanese-version');

        if (isJapaneseVersion) {
            // Switch to English version
            body.classList.remove('japanese-version');
            toggleLanguageButton.textContent = 'Switch to Japanese';
            translateToEnglish();
        } else {
            // Switch to Japanese version
            body.classList.add('japanese-version');
            toggleLanguageButton.textContent = 'Switch to English';
            translateToJapanese();
        }

        // Save language preference to localStorage
        localStorage.setItem(japaneseVersionKey, !isJapaneseVersion);
    };

    // Check if Japanese version is enabled in localStorage
    const isJapaneseVersionEnabled = localStorage.getItem(japaneseVersionKey) === 'true';
    if (isJapaneseVersionEnabled) {
        body.classList.add('japanese-version');
        toggleLanguageButton.textContent = 'Switch to English';
        translateToJapanese();
    }

    // Add event listener to the language toggle button
    toggleLanguageButton.addEventListener('click', toggleLanguage);

    // Function to translate content to Japanese
    function translateToJapanese() {
        // Replace content with Japanese text
        document.querySelectorAll('[data-en]').forEach(element => {
            element.textContent = element.getAttribute('data-jp');
        });
    }

    // Function to translate content to English
    function translateToEnglish() {
        // Replace content with English text
        document.querySelectorAll('[data-en]').forEach(element => {
            element.textContent = element.getAttribute('data-en');
        });
    }

    // Function to toggle all collapse sections
    const toggleCollapseAll = () => {
        const collapses = document.querySelectorAll('.collapse');
        const isAnyCollapsed = Array.from(collapses).some(collapse => collapse.classList.contains('show'));

        collapses.forEach(collapse => {
            if (isAnyCollapsed) {
                collapse.classList.remove('show');
            } else {
                collapse.classList.add('show');
            }
        });
    };

    // Example button to trigger toggleCollapseAll function
    const toggleAllButton = document.createElement('button');
    toggleAllButton.classList.add('btn', 'btn-primary', 'w-100', 'text-left', 'mb-3');
    toggleAllButton.innerHTML = '<i class="fas fa-chevron-down"></i> Expand/Collapse All Sections';
    toggleAllButton.addEventListener('click', toggleCollapseAll);

    // Insert the button before the first section
    const firstSection = document.querySelector('section');
    firstSection.parentNode.insertBefore(toggleAllButton, firstSection);
</script>

</body>
</html>
```


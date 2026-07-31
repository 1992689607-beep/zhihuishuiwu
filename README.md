[code.html](https://github.com/user-attachments/files/30579462/code.html)
[code.html](https://github.com/user-attachments/files/30579466/code.html)[code.html](https://github.com/user-attachments/files/30579470/code.html)[code.html](https://github.com/user-attachments/files/30579480/code.html)[code.html](https://github.com/user-attachments/files/30579487/code.html)[code.html](https://github.com/user-attachments/files/30579493/code.html)[code.html](https://github.com/user-attachments/files/30579498/code.html)<!DOCTYPE html>

<html lang="zh-CN"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>关于我们 - AquaFlow IoT</title>
<!-- Material Symbols -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Geist:wght@400;500;600&amp;family=Hanken+Grotesk:wght@600;700&amp;family=Inter:wght@400&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<!-- Tailwind Configuration -->
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "on-surface-variant": "#42474d",
                    "error": "#ba1a1a",
                    "tertiary-fixed-dim": "#afcbd8",
                    "tertiary-fixed": "#cbe7f5",
                    "on-error-container": "#93000a",
                    "inverse-primary": "#a8caef",
                    "surface-variant": "#e0e3e5",
                    "on-primary-container": "#7293b6",
                    "tertiary": "#001720",
                    "on-tertiary": "#ffffff",
                    "surface-container-highest": "#e0e3e5",
                    "outline": "#73777e",
                    "on-tertiary-fixed-variant": "#304a55",
                    "primary-fixed": "#cfe5ff",
                    "on-primary-fixed-variant": "#274969",
                    "tertiary-container": "#112c37",
                    "surface": "#f7f9fb",
                    "on-primary-fixed": "#001d34",
                    "secondary-fixed-dim": "#00daf3",
                    "on-secondary-fixed-variant": "#004f58",
                    "surface-dim": "#d8dadc",
                    "on-secondary-fixed": "#001f24",
                    "background": "#f7f9fb",
                    "secondary": "#006875",
                    "on-secondary": "#ffffff",
                    "on-primary": "#ffffff",
                    "outline-variant": "#c3c7ce",
                    "on-error": "#ffffff",
                    "inverse-on-surface": "#eff1f3",
                    "primary-container": "#002b49",
                    "surface-container-high": "#e6e8ea",
                    "secondary-fixed": "#9cf0ff",
                    "on-secondary-container": "#00616d",
                    "primary": "#001629",
                    "on-tertiary-container": "#7994a1",
                    "surface-bright": "#f7f9fb",
                    "primary-fixed-dim": "#a8caef",
                    "surface-container": "#eceef0",
                    "on-surface": "#191c1e",
                    "error-container": "#ffdad6",
                    "surface-tint": "#406182",
                    "surface-container-low": "#f2f4f6",
                    "surface-container-lowest": "#ffffff",
                    "inverse-surface": "#2d3133",
                    "on-background": "#191c1e",
                    "secondary-container": "#00e3fd",
                    "on-tertiary-fixed": "#021f29"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "spacing": {
                    "gutter": "24px",
                    "margin": "32px",
                    "container-max": "1440px",
                    "base": "4px"
            },
            "fontFamily": {
                    "headline-xl": ["Hanken Grotesk"],
                    "body-lg": ["Inter"],
                    "label-sm": ["Geist"],
                    "headline-lg": ["Hanken Grotesk"],
                    "headline-md": ["Hanken Grotesk"],
                    "data-mono": ["Geist"],
                    "body-md": ["Inter"],
                    "label-md": ["Geist"]
            },
            "fontSize": {
                    "headline-xl": ["40px", {"lineHeight": "48px", "letterSpacing": "-0.02em", "fontWeight": "700"}],
                    "body-lg": ["18px", {"lineHeight": "28px", "fontWeight": "400"}],
                    "label-sm": ["12px", {"lineHeight": "16px", "fontWeight": "600"}],
                    "headline-lg": ["32px", {"lineHeight": "40px", "fontWeight": "600"}],
                    "headline-md": ["24px", {"lineHeight": "32px", "fontWeight": "600"}],
                    "data-mono": ["14px", {"lineHeight": "20px", "fontWeight": "400"}],
                    "body-md": ["16px", {"lineHeight": "24px", "fontWeight": "400"}],
                    "label-md": ["14px", {"lineHeight": "20px", "letterSpacing": "0.01em", "fontWeight": "500"}]
            }
          }
        }
      }
    </script>
<style>
        .material-symbols-outlined {
          font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }
    </style>
</head>
<body class="bg-surface text-on-surface flex h-screen overflow-hidden font-body-md antialiased">
<!-- NavigationDrawer (Left Sidebar - Desktop) -->
<aside class="hidden md:flex flex-col bg-surface dark:bg-inverse-surface h-full w-80 bg-surface dark:bg-inverse-surface shadow-xl fixed inset-y-0 left-0 z-[60] transition-all duration-300 ease-in-out p-4">
<div class="mb-8 px-4 py-2">
<h2 class="font-headline-md text-headline-md text-primary">水务管理系统</h2>
</div>
<nav class="flex-1 space-y-2">
<!-- Inactive Tab -->
<a class="flex items-center gap-4 text-on-surface-variant hover:bg-surface-container-high rounded-full px-4 py-3 hover:bg-surface-variant dark:hover:bg-on-tertiary-fixed-variant transition-all duration-300 ease-in-out font-label-md text-label-md" href="#">
<span class="material-symbols-outlined text-[20px]">home</span>
<span>首页</span>
</a>
<!-- Inactive Tab -->
<a class="flex items-center gap-4 text-on-surface-variant hover:bg-surface-container-high rounded-full px-4 py-3 hover:bg-surface-variant dark:hover:bg-on-tertiary-fixed-variant transition-all duration-300 ease-in-out font-label-md text-label-md" href="#">
<span class="material-symbols-outlined text-[20px]">settings_input_component</span>
<span>解决方案</span>
</a>
<!-- Inactive Tab -->
<a class="flex items-center gap-4 text-on-surface-variant hover:bg-surface-container-high rounded-full px-4 py-3 hover:bg-surface-variant dark:hover:bg-on-tertiary-fixed-variant transition-all duration-300 ease-in-out font-label-md text-label-md" href="#">
<span class="material-symbols-outlined text-[20px]">inventory_2</span>
<span>产品中心</span>
</a>
<!-- Inactive Tab -->
<a class="flex items-center gap-4 text-on-surface-variant hover:bg-surface-container-high rounded-full px-4 py-3 hover:bg-surface-variant dark:hover:bg-on-tertiary-fixed-variant transition-all duration-300 ease-in-out font-label-md text-label-md" href="#">
<span class="material-symbols-outlined text-[20px]">fact_check</span>
<span>成功案例</span>
</a>
<!-- Inactive Tab -->
<a class="flex items-center gap-4 text-on-surface-variant hover:bg-surface-container-high rounded-full px-4 py-3 hover:bg-surface-variant dark:hover:bg-on-tertiary-fixed-variant transition-all duration-300 ease-in-out font-label-md text-label-md" href="#">
<span class="material-symbols-outlined text-[20px]">newspaper</span>
<span>新闻动态</span>
</a>
<!-- Active Tab (Index 5 - About Us) -->
<a class="flex items-center gap-4 bg-secondary-container text-on-secondary-container rounded-full px-4 py-3 hover:bg-surface-variant dark:hover:bg-on-tertiary-fixed-variant transition-all duration-300 ease-in-out font-label-md text-label-md" href="#">
<span class="material-symbols-outlined text-[20px]" style="font-variation-settings: 'FILL' 1;">info</span>
<span class="font-bold">关于我们</span>
</a>
<!-- Inactive Tab -->
<a class="flex items-center gap-4 text-on-surface-variant hover:bg-surface-container-high rounded-full px-4 py-3 hover:bg-surface-variant dark:hover:bg-on-tertiary-fixed-variant transition-all duration-300 ease-in-out font-label-md text-label-md" href="#">
<span class="material-symbols-outlined text-[20px]">handshake</span>
<span>合作加盟</span>
</a>
</nav>
</aside>
<!-- Main Content Area -->
<main class="flex-1 flex flex-col h-screen overflow-y-auto w-full md:pl-80 bg-surface">
<!-- TopAppBar -->
<header class="fixed top-0 w-full md:w-[calc(100%-20rem)] z-50 border-b border-outline-variant dark:border-outline shadow-sm bg-primary dark:bg-primary-container">
<div class="flex justify-between items-center px-gutter max-w-container-max mx-auto h-20">
<div class="flex items-center gap-3 text-secondary-fixed dark:text-secondary-fixed-dim cursor-pointer active:opacity-80 hover:text-secondary-container transition-colors duration-200">
<span class="material-symbols-outlined text-2xl">waves</span>
<span class="font-headline-lg text-headline-lg font-bold text-secondary-fixed tracking-tight">AQUAFLOW IoT</span>
</div>
<div class="md:hidden flex items-center text-secondary-fixed cursor-pointer active:opacity-80">
<span class="material-symbols-outlined text-2xl">menu</span>
</div>
</div>
</header>
<!-- Content Canvas -->
<div class="flex-1 mt-20 px-4 md:px-gutter py-8 max-w-container-max mx-auto w-full">
<!-- Page Header -->
<div class="mb-12">
<h1 class="font-headline-xl text-headline-xl text-primary-container mb-4">重塑工业水务管理</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-3xl">
                    AquaFlow IoT 致力于通过先进的物联网技术、边缘计算与数据分析，为全球工业企业及市政单位提供端到端的智慧水务平台。
                </p>
</div>
<!-- Section 1: Company Profile (Bento Grid) -->
<section class="grid grid-cols-1 md:grid-cols-12 gap-6 mb-16">
<!-- Main Feature Image -->
<div class="md:col-span-8 rounded-xl overflow-hidden bg-surface-container-lowest border border-outline-variant shadow-sm h-[400px] relative group">
<img class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105" data-alt="A wide-angle, highly detailed photograph of a modern, clinical industrial IoT control room. Bright, natural light-mode lighting fills the space. A large screen displays complex water management data visualizations in deep blue and cyan colors. The room features clean white surfaces, glass partitions, and a team of professional engineers in smart casual attire discussing operations. The aesthetic is corporate, high-tech, and robust, emphasizing precision and reliability in a B2B SaaS environment." src="https://lh3.googleusercontent.com/aida-public/AB6AXuAORvh_O_Ynbbmzu7USDqIrskGrv_fWfm5xH_vrBn3C2CCzFtei875bRUkHwuEIK4tDNAjz6OyvF7S4t1spYAIl6hOfXtOislgtk82EnUqy_qBFg63x0eYwPr6ymoSczMp6WgtdvJW5aH--_-KPHYNUbYpWMIanAUd9xYk4h0C2enI2QDIdQnSu8g3mx9XkbUQ1xVdbSG8rYtwAgcA_YvM-Tte-iJpMku8MvxhoQOqB3CUR68BJtFHe"/>
<div class="absolute inset-0 bg-gradient-to-t from-primary/80 to-transparent flex items-end p-8">
<div class="text-on-primary">
<h3 class="font-headline-lg text-headline-lg mb-2">连接数据，驱动未来</h3>
<p class="font-body-md text-body-md opacity-90 max-w-xl">我们的平台每日处理超过百万条水质与流量数据，确保工业生产的连续性与安全性。</p>
</div>
</div>
</div>
<!-- Core Positioning -->
<div class="md:col-span-4 flex flex-col gap-6">
<div class="bg-surface-container-lowest border border-outline-variant rounded-xl p-6 shadow-sm flex-1">
<div class="w-12 h-12 bg-secondary/10 rounded-lg flex items-center justify-center mb-4">
<span class="material-symbols-outlined text-secondary text-[28px]">hub</span>
</div>
<h4 class="font-headline-md text-headline-md text-primary-container mb-2">核心定位</h4>
<p class="font-body-md text-body-md text-on-surface-variant">
                            工业级 IoT SaaS 提供商。我们不制造硬件，而是赋予硬件智能，打破设备孤岛，实现水务资产的全生命周期管理。
                        </p>
</div>
<div class="bg-primary-container text-on-primary rounded-xl p-6 shadow-sm flex-1 relative overflow-hidden">
<div class="absolute -right-4 -top-4 opacity-10">
<span class="material-symbols-outlined text-[120px]">water_drop</span>
</div>
<h4 class="font-headline-md text-headline-md mb-2 relative z-10">服务领域</h4>
<ul class="space-y-2 mt-4 font-body-md text-body-md relative z-10 text-inverse-primary">
<li class="flex items-center gap-2"><span class="material-symbols-outlined text-[18px] text-secondary-fixed">check_circle</span>市政污水处理厂</li>
<li class="flex items-center gap-2"><span class="material-symbols-outlined text-[18px] text-secondary-fixed">check_circle</span>化工园区水监测</li>
<li class="flex items-center gap-2"><span class="material-symbols-outlined text-[18px] text-secondary-fixed">check_circle</span>农业智能灌溉网络</li>
</ul>
</div>
</div>
</section>
<!-- Section 2: Qualifications & Honors -->
<section class="mb-16">
<div class="mb-8">
<h2 class="font-headline-lg text-headline-lg text-primary-container inline-flex items-center gap-2">
<span class="material-symbols-outlined text-secondary">verified</span>
                        资质与荣誉
                    </h2>
<div class="h-1 w-12 bg-secondary mt-2"></div>
</div>
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
<!-- Qual Card 1 -->
<div class="bg-surface-container-lowest border border-outline-variant rounded-xl p-6 shadow-sm hover:shadow-md transition-shadow flex items-start gap-4">
<span class="material-symbols-outlined text-[32px] text-secondary">workspace_premium</span>
<div>
<h5 class="font-label-md text-label-md font-bold text-on-surface">高新技术企业</h5>
<p class="font-data-mono text-data-mono text-on-surface-variant text-xs mt-1">国家级认证证书</p>
</div>
</div>
<!-- Qual Card 2 -->
<div class="bg-surface-container-lowest border border-outline-variant rounded-xl p-6 shadow-sm hover:shadow-md transition-shadow flex items-start gap-4">
<span class="material-symbols-outlined text-[32px] text-secondary">policy</span>
<div>
<h5 class="font-label-md text-label-md font-bold text-on-surface">ISO 9001</h5>
<p class="font-data-mono text-data-mono text-on-surface-variant text-xs mt-1">质量管理体系认证</p>
</div>
</div>
<!-- Qual Card 3 -->
<div class="bg-surface-container-lowest border border-outline-variant rounded-xl p-6 shadow-sm hover:shadow-md transition-shadow flex items-start gap-4">
<span class="material-symbols-outlined text-[32px] text-secondary">memory</span>
<div>
<h5 class="font-label-md text-label-md font-bold text-on-surface">20+ 核心专利</h5>
<p class="font-data-mono text-data-mono text-on-surface-variant text-xs mt-1">IoT边缘计算领域</p>
</div>
</div>
<!-- Qual Card 4 -->
<div class="bg-surface-container-lowest border border-outline-variant rounded-xl p-6 shadow-sm hover:shadow-md transition-shadow flex items-start gap-4">
<span class="material-symbols-outlined text-[32px] text-secondary">security</span>
<div>
<h5 class="font-label-md text-label-md font-bold text-on-surface">等保三级认证</h5>
<p class="font-data-mono text-data-mono text-on-surface-variant text-xs mt-1">SaaS平台数据安全</p>
</div>
</div>
</div>
</section>
<!-- Section 3: Development Timeline & Section 4: Core Team (Two column layout on large screens) -->
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 mb-16">
<!-- Timeline -->
<section>
<div class="mb-8">
<h2 class="font-headline-lg text-headline-lg text-primary-container inline-flex items-center gap-2">
<span class="material-symbols-outlined text-secondary">timeline</span>
                            发展历程
                        </h2>
</div>
<div class="relative border-l-2 border-surface-variant ml-3 md:ml-4 space-y-8">
<!-- Node 1 -->
<div class="relative pl-8">
<div class="absolute w-4 h-4 bg-surface border-2 border-secondary rounded-full -left-[9px] top-1"></div>
<h4 class="font-headline-md text-headline-md text-secondary-container mb-1">2018</h4>
<h5 class="font-label-md text-label-md font-bold text-on-surface">公司创立</h5>
<p class="font-body-md text-body-md text-on-surface-variant mt-2">AquaFlow 团队组建，确立工业级水务物联网研发方向，获得首轮天使投资。</p>
</div>
<!-- Node 2 -->
<div class="relative pl-8">
<div class="absolute w-4 h-4 bg-surface border-2 border-secondary rounded-full -left-[9px] top-1"></div>
<h4 class="font-headline-md text-headline-md text-secondary-container mb-1">2020</h4>
<h5 class="font-label-md text-label-md font-bold text-on-surface">首个千万级项目交付</h5>
<p class="font-body-md text-body-md text-on-surface-variant mt-2">成功为华东地区某大型化工园区部署全要素水质监测网络，系统稳定运行。</p>
</div>
<!-- Node 3 -->
<div class="relative pl-8">
<div class="absolute w-4 h-4 bg-surface border-2 border-secondary rounded-full -left-[9px] top-1"></div>
<h4 class="font-headline-md text-headline-md text-secondary-container mb-1">2022</h4>
<h5 class="font-label-md text-label-md font-bold text-on-surface">SaaS 平台 2.0 发布</h5>
<p class="font-body-md text-body-md text-on-surface-variant mt-2">完成从定制化项目向标准化 SaaS 产品的转型，引入 AI 异常预测算法。</p>
</div>
<!-- Node 4 -->
<div class="relative pl-8">
<div class="absolute w-4 h-4 bg-secondary rounded-full -left-[9px] top-1 ring-4 ring-secondary/20"></div>
<h4 class="font-headline-md text-headline-md text-primary-container mb-1">2023 至今</h4>
<h5 class="font-label-md text-label-md font-bold text-on-surface">百厂互联</h5>
<p class="font-body-md text-body-md text-on-surface-variant mt-2">服务超过 100 家大型水务处理厂及工业园区，每日处理数据突破数千万条，成为行业标杆。</p>
</div>
</div>
</section>
<!-- Core Team -->
<section>
<div class="mb-8">
<h2 class="font-headline-lg text-headline-lg text-primary-container inline-flex items-center gap-2">
<span class="material-symbols-outlined text-secondary">groups</span>
                            核心团队
                        </h2>
</div>
<div class="space-y-6">
<!-- Profile 1 -->
<div class="bg-surface-container-lowest border border-outline-variant rounded-xl p-4 shadow-sm flex items-center gap-6">
<div class="w-24 h-24 rounded-full overflow-hidden shrink-0 border-2 border-surface-variant">
<img class="w-full h-full object-cover" data-alt="A professional corporate headshot of an Asian male executive in his 40s. He is wearing a sharp, tailored navy blue suit with a crisp white shirt. The background is a slightly blurred, modern office environment with bright, cool lighting. The mood is confident, trustworthy, and authoritative, fitting for the CEO of a cutting-edge industrial IoT technology company." src="https://lh3.googleusercontent.com/aida-public/AB6AXuD6IY8rFlnoFJ7C90t6HV5yUi_P-NTcCUL_mEuCCYdZ7POv2aAx3BZCrPP-XYTKsTPzdcJ7N-siruZuIY8pPseN6Asx77DrwEWOOaJWghE3TVPLzRt4NulF20akp3n8zqWTIYpw_DHuFBUDhW8zIwf4aarvcw94mLd1M2Vahq7YhoHHDi6o-b8uMKeYDTPw9xTJG-CELddrAqz8hLex4hM9NwJY5FuEFWeHyRn3aJ_O6NWAQHvu7Cob"/>
</div>
<div>
<h4 class="font-headline-md text-headline-md text-on-surface mb-1">张建国 (David Zhang)</h4>
<span class="inline-block bg-primary-container/10 text-primary-container font-label-sm px-2 py-1 rounded text-xs mb-2">创始人 &amp; CEO</span>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">
                                    拥有15年工业自动化行业经验，曾任跨国公司大中华区物联网事业部总监。致力于将尖端传感技术与数据分析深度结合。
                                </p>
</div>
</div>
<!-- Profile 2 -->
<div class="bg-surface-container-lowest border border-outline-variant rounded-xl p-4 shadow-sm flex items-center gap-6">
<div class="w-24 h-24 rounded-full overflow-hidden shrink-0 border-2 border-surface-variant">
<img class="w-full h-full object-cover" data-alt="A professional corporate headshot of an Asian female Chief Technology Officer in her late 30s. She is wearing a modern, minimalist light gray blazer over a white blouse. The background features a subtle hint of a server room or high-tech lab with soft blue lighting. The overall lighting is bright and clean. She exudes intelligence, innovation, and reliability in a high-end B2B context." src="https://lh3.googleusercontent.com/aida-public/AB6AXuDkZzYHu9UJpnkwDzmqMGvr3NZ54yZBZfBjz4kgHZCIVvbFwaIRKh97Ty0e9a0K_VdoTWnYTZuT7u6C_0IaSbr3SGP72OcLVBotmNXXQv-oNzLiX8b_E5aANRk_zi5xtIueQEkQe6JvEl2U9RjsA8ryEJHuDxSvV_6cPOfRAFNEG19BWM2qeJi8Xs-hK9YDwkaYczPMFDeSKjSiy9Hdz-a46sC6vQdXc6kYf8hYOvvddDCemS-poHe-"/>
</div>
<div>
<h4 class="font-headline-md text-headline-md text-on-surface mb-1">李雪 (Sarah Li)</h4>
<span class="inline-block bg-secondary/10 text-secondary font-label-sm px-2 py-1 rounded text-xs mb-2">联合创始人 &amp; CTO</span>
<p class="font-body-md text-body-md text-on-surface-variant text-sm">
                                    计算机科学博士，专注于高并发数据流处理及边缘计算架构设计。主导研发了AquaFlow核心SaaS平台的底层架构。
                                </p>
</div>
</div>
</div>
</section>
</div>
</div>
<!-- Footer (Inside main content to scroll with it) -->
<footer class="w-full bg-primary dark:bg-tertiary-container border-t border-on-primary-fixed-variant mt-auto">
<div class="grid grid-cols-1 md:grid-cols-4 gap-8 px-gutter py-12 max-w-container-max mx-auto text-on-primary dark:text-tertiary-fixed font-body-md text-body-md">
<!-- Brand Info -->
<div class="md:col-span-1">
<h3 class="font-headline-md text-headline-md text-secondary-fixed mb-4">AQUAFLOW IoT</h3>
<p class="text-surface-variant opacity-80 text-sm">
                        引领工业水务的数字化转型，构建透明、高效、可持续的水资源管理未来。
                    </p>
</div>
<!-- Links -->
<div class="md:col-span-2 grid grid-cols-2 gap-4">
<div>
<h4 class="font-bold text-on-primary mb-3">快捷链接</h4>
<ul class="space-y-2">
<li><a class="text-surface-variant hover:text-secondary-fixed-dim underline transition-all opacity-100 hover:opacity-80" href="#">联系我们</a></li>
<li><a class="text-surface-variant hover:text-secondary-fixed-dim underline transition-all opacity-100 hover:opacity-80" href="#">关于我们</a></li>
</ul>
</div>
<div>
<h4 class="font-bold text-on-primary mb-3">法律条款</h4>
<ul class="space-y-2">
<li><a class="text-surface-variant hover:text-secondary-fixed-dim underline transition-all opacity-100 hover:opacity-80" href="#">隐私政策</a></li>
<li><a class="text-surface-variant hover:text-secondary-fixed-dim underline transition-all opacity-100 hover:opacity-80" href="#">服务条款</a></li>
</ul>
</div>
</div>
<!-- Action/Copyright -->
<div class="md:col-span-1 flex flex-col justify-between">
<div>
<a class="text-surface-variant hover:text-secondary-fixed-dim underline transition-all opacity-100 hover:opacity-80 block mb-2" href="#">合作加盟</a>
<a class="text-surface-variant hover:text-secondary-fixed-dim underline transition-all opacity-100 hover:opacity-80 block" href="#">加入我们</a>
</div>
<div class="mt-8 text-xs text-surface-variant opacity-60">
                        © 2024 AquaFlow Smart Water Management. All Rights Reserved.
                    </div>
</div>
</div>
</footer>
</main>
</body></html>

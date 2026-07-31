[deepseek_html_20260731_0ee343.html](https://github.com/user-attachments/files/30584681/deepseek_html_20260731_0ee343.html)
<!DOCTYPE html>

<html class="dark" lang="zh-CN"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Smart Water Management</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
          darkMode: "class",
          theme: {
            extend: {
              "colors": {
                      "on-tertiary-fixed": "#111d23",
                      "outline": "#849396",
                      "secondary-container": "#343d96",
                      "tertiary": "#e1eef6",
                      "primary-fixed-dim": "#00daf3",
                      "surface-variant": "#313537",
                      "surface-container-highest": "#313537",
                      "secondary-fixed-dim": "#bdc2ff",
                      "secondary": "#bdc2ff",
                      "on-secondary-fixed-variant": "#343d96",
                      "on-surface": "#e0e3e5",
                      "on-primary-fixed-variant": "#004f58",
                      "on-error-container": "#ffdad6",
                      "on-secondary-fixed": "#000767",
                      "on-primary-container": "#00626e",
                      "primary": "#c3f5ff",
                      "on-tertiary-fixed-variant": "#3c494f",
                      "surface-bright": "#363a3c",
                      "on-tertiary": "#263238",
                      "surface-container-low": "#181c1e",
                      "surface-container": "#1c2022",
                      "surface-container-high": "#262b2c",
                      "background": "#101416",
                      "surface": "#101416",
                      "inverse-surface": "#e0e3e5",
                      "on-secondary": "#1b247f",
                      "on-background": "#e0e3e5",
                      "error": "#ffb4ab",
                      "surface-dim": "#101416",
                      "surface-container-lowest": "#0b0f10",
                      "on-primary-fixed": "#001f24",
                      "surface-tint": "#00daf3",
                      "on-surface-variant": "#bac9cc",
                      "inverse-primary": "#006875",
                      "tertiary-fixed": "#d7e4ec",
                      "on-secondary-container": "#a8afff",
                      "primary-container": "#00e5ff",
                      "on-primary": "#00363d",
                      "secondary-fixed": "#e0e0ff",
                      "inverse-on-surface": "#2d3133",
                      "tertiary-fixed-dim": "#bbc8d0",
                      "error-container": "#93000a",
                      "on-tertiary-container": "#4e5b61",
                      "on-error": "#690005",
                      "outline-variant": "#3b494c",
                      "primary-fixed": "#9cf0ff",
                      "tertiary-container": "#c5d2da"
              },
              "borderRadius": {
                      "DEFAULT": "0.25rem",
                      "lg": "0.5rem",
                      "xl": "0.75rem",
                      "full": "9999px"
              },
              "spacing": {
                      "margin-desktop": "64px",
                      "margin-mobile": "20px",
                      "stack-md": "16px",
                      "stack-lg": "32px",
                      "gutter": "24px",
                      "stack-sm": "8px",
                      "container-max": "1280px"
              },
              "fontFamily": {
                      "body-md": [
                              "Inter"
                      ],
                      "body-lg": [
                              "Inter"
                      ],
                      "headline-lg": [
                              "Inter"
                      ],
                      "metric-xl": [
                              "Inter"
                      ],
                      "headline-lg-mobile": [
                              "Inter"
                      ],
                      "display-xl": [
                              "Inter"
                      ],
                      "label-sm": [
                              "Inter"
                      ]
              },
              "fontSize": {
                      "body-md": [
                              "16px",
                              {
                                      "lineHeight": "24px",
                                      "fontWeight": "400"
                              }
                      ],
                      "body-lg": [
                              "18px",
                              {
                                      "lineHeight": "28px",
                                      "fontWeight": "400"
                              }
                      ],
                      "headline-lg": [
                              "48px",
                              {
                                      "lineHeight": "56px",
                                      "letterSpacing": "-0.01em",
                                      "fontWeight": "600"
                              }
                      ],
                      "metric-xl": [
                              "40px",
                              {
                                      "lineHeight": "48px",
                                      "letterSpacing": "0.02em",
                                      "fontWeight": "700"
                              }
                      ],
                      "headline-lg-mobile": [
                              "32px",
                              {
                                      "lineHeight": "40px",
                                      "fontWeight": "600"
                              }
                      ],
                      "display-xl": [
                              "72px",
                              {
                                      "lineHeight": "80px",
                                      "letterSpacing": "-0.02em",
                                      "fontWeight": "700"
                              }
                      ],
                      "label-sm": [
                              "12px",
                              {
                                      "lineHeight": "16px",
                                      "letterSpacing": "0.05em",
                                      "fontWeight": "600"
                              }
                      ]
              }
      },
          },
        }
    </script>
<style>
        .glass-panel {
            background: rgba(38, 50, 56, 0.6);
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .text-gradient {
            background: linear-gradient(to right, #00e5ff, #00daf3);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .hover-glow:hover {
            box-shadow: 0 0 40px rgba(0, 229, 255, 0.15);
        }
    </style>
</head>
<body class="bg-background text-on-background font-body-md min-h-screen overflow-x-hidden">
<!-- TopNavBar -->
<header class="fixed top-0 w-full z-50 bg-transparent backdrop-blur-md dark:bg-transparent border-b border-outline-variant/20 transition-all duration-300">
<div class="flex justify-between items-center w-full px-margin-desktop py-4 max-w-container-max mx-auto">
<div class="font-headline-lg-mobile text-headline-lg-mobile font-bold text-primary dark:text-primary-fixed-dim">
                SmartWater HQ
            </div>
<nav class="hidden md:flex gap-8">
<a class="text-primary font-bold border-b-2 border-primary pb-1 hover:bg-white/10 dark:hover:bg-black/20 transition-all duration-300" href="#">首页</a>
<a class="text-on-surface/80 hover:text-primary transition-colors hover:bg-white/10 dark:hover:bg-black/20 duration-300" href="#">解决方案</a>
<a class="text-on-surface/80 hover:text-primary transition-colors hover:bg-white/10 dark:hover:bg-black/20 duration-300" href="#">产品中心</a>
<a class="text-on-surface/80 hover:text-primary transition-colors hover:bg-white/10 dark:hover:bg-black/20 duration-300" href="#">成功案例</a>
<a class="text-on-surface/80 hover:text-primary transition-colors hover:bg-white/10 dark:hover:bg-black/20 duration-300" href="#">新闻动态</a>
<a class="text-on-surface/80 hover:text-primary transition-colors hover:bg-white/10 dark:hover:bg-black/20 duration-300" href="#">关于我们</a>
<a class="text-on-surface/80 hover:text-primary transition-colors hover:bg-white/10 dark:hover:bg-black/20 duration-300" href="#">合作加盟</a>
</nav>
<button class="bg-gradient-to-r from-primary-container to-primary-fixed-dim text-on-primary-container font-bold px-6 py-2 rounded-full hover:shadow-[0_0_20px_rgba(0,229,255,0.4)] transition-all">
                预约演示
            </button>
</div>
</header>
<!-- Hero Section -->
<section class="relative pt-32 pb-24 md:pt-48 md:pb-32 px-margin-mobile md:px-margin-desktop min-h-screen flex items-center justify-center">
<!-- Background Placeholder -->
<div class="absolute inset-0 z-0">
<img class="w-full h-full object-cover opacity-40 mix-blend-screen" data-alt="A highly detailed, cinematic 3D visualization of a modern, futuristic water treatment plant at dusk. Glowing cyan data streams overlay the industrial architecture, emphasizing real-time digital twin monitoring. The scene is lit with moody deep blues and vibrant cyan highlights, creating a high-tech 'command center' atmosphere. Corporate modern aesthetic with glassmorphism UI elements floating subtly in the foreground." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBQ7zLsx3HQDfUpCQiLt_-LuQNPQqMj08XUX9p2htaIlvScBcBzkFeN8er7TlGU1tSCCzi7Wfb5MaUshr6DTQ08_hpZO2KmeV5T09VLj3l9xL2EPXit_a0IA0uq6fJvwtcHx1BNldDzVThz8Zytj6H-lHwnE47G_mKRQ_fnnlPzAKSMxQJ9SNt0-3lQEgRzcznS5G6NwktwjkwtF3QCUnwult0oZhvQaWF4BDG3PRGnqKAhJ2hY_RgL7X9JiDn4qO3tBCs"/>
<div class="absolute inset-0 bg-gradient-to-b from-background via-background/80 to-background"></div>
</div>
<div class="relative z-10 max-w-container-max mx-auto w-full text-center md:text-left flex flex-col md:flex-row items-center gap-12">
<div class="flex-1 space-y-6">
<h1 class="font-display-xl text-display-xl font-bold text-on-background leading-tight">
                    让每一座污水厂都拥有<br/>
<span class="text-gradient">数字化大脑</span>
</h1>
<p class="font-body-lg text-body-lg text-on-surface-variant max-w-2xl">
                    覆盖监控→分析→运维→决策全链路，助力污水厂综合运维成本降低15%~25%
                </p>
<div class="pt-4">
<button class="bg-gradient-to-r from-primary-container to-primary-fixed-dim text-on-primary-container font-bold px-8 py-4 rounded-full text-lg hover:shadow-[0_0_30px_rgba(0,229,255,0.5)] transition-all flex items-center gap-2">
                        立即获取方案 <span class="material-symbols-outlined">arrow_forward</span>
</button>
</div>
</div>
<div class="flex-1 w-full grid grid-cols-2 gap-4">
<div class="glass-panel p-6 rounded-2xl flex flex-col items-center justify-center hover-glow transition-all">
<span class="font-metric-xl text-metric-xl text-primary-container">300+</span>
<span class="font-label-sm text-label-sm text-on-surface-variant mt-2 uppercase">服务水厂 (座)</span>
</div>
<div class="glass-panel p-6 rounded-2xl flex flex-col items-center justify-center hover-glow transition-all">
<span class="font-metric-xl text-metric-xl text-primary-container">50,000+</span>
<span class="font-label-sm text-label-sm text-on-surface-variant mt-2 uppercase">设备连接 (台)</span>
</div>
<div class="glass-panel p-6 rounded-2xl flex flex-col items-center justify-center hover-glow transition-all">
<span class="font-metric-xl text-metric-xl text-primary-container">20%+</span>
<span class="font-label-sm text-label-sm text-on-surface-variant mt-2 uppercase">平均节能</span>
</div>
<div class="glass-panel p-6 rounded-2xl flex flex-col items-center justify-center hover-glow transition-all">
<span class="font-metric-xl text-metric-xl text-primary-container">98%</span>
<span class="font-label-sm text-label-sm text-on-surface-variant mt-2 uppercase">客户续费率</span>
</div>
</div>
</div>
</section>
<!-- Core Value Section -->
<section class="py-24 px-margin-mobile md:px-margin-desktop bg-surface-container-lowest">
<div class="max-w-container-max mx-auto">
<h2 class="font-headline-lg text-headline-lg text-center mb-16">核心价值呈现</h2>
<div class="grid grid-cols-1 md:grid-cols-3 gap-8">
<!-- Card 1 -->
<div class="glass-panel p-8 rounded-3xl relative overflow-hidden group hover:-translate-y-2 transition-transform duration-300">
<div class="absolute -right-10 -top-10 w-32 h-32 bg-primary/20 rounded-full blur-3xl group-hover:bg-primary/40 transition-colors"></div>
<div class="w-14 h-14 rounded-full bg-surface-variant/50 flex items-center justify-center mb-6 border border-white/10">
<span class="material-symbols-outlined text-primary text-3xl">warning</span>
</div>
<h3 class="font-headline-lg-mobile text-headline-lg-mobile mb-4">实时预警，<br/>杜绝超标风险</h3>
<p class="text-on-surface-variant font-body-md mb-6">毫秒级数据采集，智能研判水质变化趋势，防患于未然，确保出水100%达标。</p>
<a class="text-primary flex items-center gap-2 font-bold hover:text-primary-container" href="#">
                        了解详情 <span class="material-symbols-outlined">arrow_right_alt</span>
</a>
</div>
<!-- Card 2 -->
<div class="glass-panel p-8 rounded-3xl relative overflow-hidden group hover:-translate-y-2 transition-transform duration-300">
<div class="absolute -right-10 -top-10 w-32 h-32 bg-primary/20 rounded-full blur-3xl group-hover:bg-primary/40 transition-colors"></div>
<div class="w-14 h-14 rounded-full bg-surface-variant/50 flex items-center justify-center mb-6 border border-white/10">
<span class="material-symbols-outlined text-primary text-3xl">analytics</span>
</div>
<h3 class="font-headline-lg-mobile text-headline-lg-mobile mb-4">智能分析，<br/>精准降本增效</h3>
<p class="text-on-surface-variant font-body-md mb-6">AI算法优化加药量与曝气策略，拒绝经验盲干，实现精细化运营管理。</p>
<a class="text-primary flex items-center gap-2 font-bold hover:text-primary-container" href="#">
                        了解详情 <span class="material-symbols-outlined">arrow_right_alt</span>
</a>
</div>
<!-- Card 3 -->
<div class="glass-panel p-8 rounded-3xl relative overflow-hidden group hover:-translate-y-2 transition-transform duration-300">
<div class="absolute -right-10 -top-10 w-32 h-32 bg-primary/20 rounded-full blur-3xl group-hover:bg-primary/40 transition-colors"></div>
<div class="w-14 h-14 rounded-full bg-surface-variant/50 flex items-center justify-center mb-6 border border-white/10">
<span class="material-symbols-outlined text-primary text-3xl">settings_suggest</span>
</div>
<h3 class="font-headline-lg-mobile text-headline-lg-mobile mb-4">设备全生命周期，<br/>资产不流失</h3>
<p class="text-on-surface-variant font-body-md mb-6">建立设备数字档案，预测性维护提醒，延长核心设备使用寿命。</p>
<a class="text-primary flex items-center gap-2 font-bold hover:text-primary-container" href="#">
                        了解详情 <span class="material-symbols-outlined">arrow_right_alt</span>
</a>
</div>
</div>
</div>
</section>
<!-- Solution Grid -->
<section class="py-24 px-margin-mobile md:px-margin-desktop">
<div class="max-w-container-max mx-auto">
<h2 class="font-headline-lg text-headline-lg text-center mb-16">多场景覆盖</h2>
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div class="relative h-64 rounded-3xl overflow-hidden group">
<div class="absolute inset-0 bg-surface-container-high/80 z-10 group-hover:bg-surface-container-high/60 transition-colors"></div>
<img class="absolute inset-0 w-full h-full object-cover" data-alt="A highly detailed wide-angle shot of a large-scale municipal wastewater treatment plant. Concrete sedimentation tanks filled with water are arranged symmetrically. The environment is illuminated by bright, cool daylight. The aesthetic is clean, industrial, and highly functional, representing 'Municipal Sewage' treatment. The image uses a muted palette of greys, concrete textures, and reflective water surfaces." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBOm40lE6TGxiS0p50Q6gj2xwzQh0xNiCM31fw-WUwWLm483jXiwctMR0qRszcr-hECpylHrs5srFjnzyjsG1Z_53H2D4UlkBTX1VnGkCwtJSxwlljzc5HLg_WcuYJIZ4aMMQylIdwZwhjeyL4b9Ik56NUfnubMiADLEZIVHQomcxh-MrsG8X3B-cZPxjrfEoFgRLTSogDW2sfzIB_ENR2PMb4UCZJFgXzTyhS9OpwahPn6wJycLzyb-A"/>
<div class="absolute inset-0 z-20 p-8 flex flex-col justify-end">
<h3 class="font-headline-lg-mobile text-headline-lg-mobile font-bold">市政污水</h3>
<p class="text-on-surface-variant mt-2">大型水厂集约化管理，保障城市生命线运行安全。</p>
</div>
</div>
<div class="relative h-64 rounded-3xl overflow-hidden group">
<div class="absolute inset-0 bg-surface-container-high/80 z-10 group-hover:bg-surface-container-high/60 transition-colors"></div>
<img class="absolute inset-0 w-full h-full object-cover" data-alt="An industrial complex focusing on wastewater treatment within a modern industrial park. Complex piping systems, chemical storage tanks, and high-tech filtration units are visible. The lighting is cinematic and dramatic, emphasizing the complex engineering involved in 'Industrial Park Wastewater' treatment. The color palette features metallic silvers, safety yellows, and dark shadows." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBhuW4tvFcwVt8M7RkTeTVDVfA3qKl6lGgfoyhYSRQYhV8xYQ-QrmX_ejE8UsM4FYMulF8ApMzdjokRsvpzCB6eRkx3VrbeatungmLUVhWpZRZS1u-MR-H3bk2MAGEIODI_z1-ioov0guX6Ff-P5rVFlS7QZ71oKalcRhP0KJMLd-ubNlnf0y-7dudixFGvBv5Lj3wAU9QKrYJjqm7uzhlm49VYgVwT8KBSzCwji2uxg4v8RTqfeTLpQQ"/>
<div class="absolute inset-0 z-20 p-8 flex flex-col justify-end">
<h3 class="font-headline-lg-mobile text-headline-lg-mobile font-bold">工业园区废水</h3>
<p class="text-on-surface-variant mt-2">应对复杂水质波动，强化毒性预警与特殊工艺控制。</p>
</div>
</div>
<div class="relative h-64 rounded-3xl overflow-hidden group">
<div class="absolute inset-0 bg-surface-container-high/80 z-10 group-hover:bg-surface-container-high/60 transition-colors"></div>
<img class="absolute inset-0 w-full h-full object-cover" data-alt="A compact, modular integrated water treatment facility situated in a rural or township setting. Surrounded by subtle greenery, the metal container-like structure represents 'Township Integrated' treatment. The lighting is natural and soft, showcasing an eco-friendly approach to distributed water management. Colors are harmonious greens, earthy tones, and clean metal finishes." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBdnU5484Yf3B76NT75AN6hxgdz1tA6mX8Iu2nH8-nWT6i4RmydKgficejSu2vP_LUa7MkB0z6YaJw8ZsGIQTBlljRNH3CmtLsKVbUbJQZ1On4InzSLNOyggK_qnqhQ4LG2UnnYMEGTSG6UHAzblcy4DUK4-zCLJuSCp-GGaAjuBA7MgFEJ6bqFjH6Wdl77nEJ2iYXzI7qNkwPtWkIuzFxj9NpIzkJW8XR6v9FaAdmaxWRIjwj_yGbL7g"/>
<div class="absolute inset-0 z-20 p-8 flex flex-col justify-end">
<h3 class="font-headline-lg-mobile text-headline-lg-mobile font-bold">乡镇一体化</h3>
<p class="text-on-surface-variant mt-2">无人值守，云端统管，解决分散式站点运维难题。</p>
</div>
</div>
<div class="relative h-64 rounded-3xl overflow-hidden group">
<div class="absolute inset-0 bg-surface-container-high/80 z-10 group-hover:bg-surface-container-high/60 transition-colors"></div>
<img class="absolute inset-0 w-full h-full object-cover" data-alt="A close-up view of heavy-duty water pumps and lift station infrastructure. Large mechanical components, thick pipes, and digital sensor nodes are prominent. The lighting is stark and technical, highlighting the raw power and engineering required for 'Pump Station Lifting'. Deep indigos and cyan accents define the industrial technology aesthetic." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCKJWToWCYKzMXET0LRsU8dPIWPpQeA_Sb5laszRDFmjNbxgIF0SdMgA87EF8icVK9wAIsxk6MhdRUhVP6Q6BOMtts6cPuD6ODZH3l-m3pmmrFBf2_TUos1w-zc8wAffEwKl-TOZqPlDYjppSNxRG3gprIgnJ-i9H6BqEbnhdKcryatZYeYl_znf-7slYIUKySnsa27iaAOrKqDNC-2N0Y2cyHP1D84fhLFm1AGsRR6EEYK-plB6YtQ2A"/>
<div class="absolute inset-0 z-20 p-8 flex flex-col justify-end">
<h3 class="font-headline-lg-mobile text-headline-lg-mobile font-bold">泵站提升</h3>
<p class="text-on-surface-variant mt-2">水位联动控制，能耗最优调度，保障输送管网顺畅。</p>
</div>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="bg-surface-container-lowest dark:bg-background pt-16 pb-8 border-t border-outline-variant/10">
<div class="max-w-container-max mx-auto px-margin-desktop grid grid-cols-1 md:grid-cols-4 gap-gutter mb-12">
<div class="col-span-1 md:col-span-2">
<div class="font-headline-lg text-headline-lg text-primary mb-4">SmartWater HQ</div>
<p class="text-on-surface-variant font-body-md max-w-sm mb-6">让每一座污水厂都拥有数字化大脑。专注工业与市政水处理智能化解决方案。</p>
<div class="flex gap-4">
<!-- Lead Gen Form Small -->
<input class="bg-surface-variant/30 border-b border-outline-variant/50 focus:border-primary px-4 py-2 text-on-surface focus:outline-none focus:ring-0 rounded-t-md w-64" placeholder="输入邮箱获取方案..." type="email"/>
<button class="bg-primary/10 text-primary hover:bg-primary/20 px-4 py-2 rounded-md transition-colors border border-primary/30">
                        订阅
                     </button>
</div>
</div>
<div class="flex flex-col gap-3">
<h4 class="font-bold text-on-surface mb-2">快速链接</h4>
<a class="text-on-surface-variant hover:text-primary transition-colors" href="#">首页</a>
<a class="text-on-surface-variant hover:text-primary transition-colors" href="#">解决方案</a>
<a class="text-on-surface-variant hover:text-primary transition-colors" href="#">产品中心</a>
</div>
<div class="flex flex-col gap-3">
<h4 class="font-bold text-on-surface mb-2">了解更多</h4>
<a class="text-on-surface-variant hover:text-primary transition-colors" href="#">关于我们</a>
<a class="text-on-surface-variant hover:text-primary transition-colors" href="#">加入我们</a>
<a class="text-on-surface-variant hover:text-primary transition-colors" href="#">联系我们</a>
<a class="text-on-surface-variant hover:text-primary transition-colors" href="#">隐私政策</a>
</div>
</div>
<div class="max-w-container-max mx-auto px-margin-desktop pt-8 border-t border-outline-variant/10 text-center md:text-left text-on-surface-variant font-body-md">
            © 2024 Smart Water Management Systems. All rights reserved.
        </div>
</footer>
</body></html>
[deepseek_html_20260730_0ee343.html](https://github.com/user-attachments/files/30584701/deepseek_html_20260730_0ee343.html)
<!DOCTYPE html><html class="dark" lang="zh-CN"><head>
<meta charset="utf-8">
<meta content="width=device-width, initial-scale=1.0" name="viewport">
<title>Solutions - SmartWater HQ</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&amp;display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet">
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-tertiary-fixed": "#111d23",
                        "outline": "#849396",
                        "secondary-container": "#343d96",
                        "tertiary": "#e1eef6",
                        "primary-fixed-dim": "#00daf3",
                        "surface-variant": "#313537",
                        "surface-container-highest": "#313537",
                        "secondary-fixed-dim": "#bdc2ff",
                        "secondary": "#bdc2ff",
                        "on-secondary-fixed-variant": "#343d96",
                        "on-surface": "#e0e3e5",
                        "on-primary-fixed-variant": "#004f58",
                        "on-error-container": "#ffdad6",
                        "on-secondary-fixed": "#000767",
                        "on-primary-container": "#00626e",
                        "primary": "#c3f5ff",
                        "on-tertiary-fixed-variant": "#3c494f",
                        "surface-bright": "#363a3c",
                        "on-tertiary": "#263238",
                        "surface-container-low": "#181c1e",
                        "surface-container": "#1c2022",
                        "surface-container-high": "#262b2c",
                        "background": "#101416",
                        "surface": "#101416",
                        "inverse-surface": "#e0e3e5",
                        "on-secondary": "#1b247f",
                        "on-background": "#e0e3e5",
                        "error": "#ffb4ab",
                        "surface-dim": "#101416",
                        "surface-container-lowest": "#0b0f10",
                        "on-primary-fixed": "#001f24",
                        "surface-tint": "#00daf3",
                        "on-surface-variant": "#bac9cc",
                        "inverse-primary": "#006875",
                        "tertiary-fixed": "#d7e4ec",
                        "on-secondary-container": "#a8afff",
                        "primary-container": "#00e5ff",
                        "on-primary": "#00363d",
                        "secondary-fixed": "#e0e0ff",
                        "inverse-on-surface": "#2d3133",
                        "tertiary-fixed-dim": "#bbc8d0",
                        "error-container": "#93000a",
                        "on-tertiary-container": "#4e5b61",
                        "on-error": "#690005",
                        "outline-variant": "#3b494c",
                        "primary-fixed": "#9cf0ff",
                        "tertiary-container": "#c5d2da"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "margin-desktop": "64px",
                        "margin-mobile": "20px",
                        "stack-md": "16px",
                        "stack-lg": "32px",
                        "gutter": "24px",
                        "stack-sm": "8px",
                        "container-max": "1280px"
                    },
                    "fontFamily": {
                        "body-md": ["Inter"],
                        "body-lg": ["Inter"],
                        "headline-lg": ["Inter"],
                        "metric-xl": ["Inter"],
                        "headline-lg-mobile": ["Inter"],
                        "display-xl": ["Inter"],
                        "label-sm": ["Inter"]
                    },
                    "fontSize": {
                        "body-md": ["16px", { "lineHeight": "24px", "fontWeight": "400" }],
                        "body-lg": ["18px", { "lineHeight": "28px", "fontWeight": "400" }],
                        "headline-lg": ["48px", { "lineHeight": "56px", "letterSpacing": "-0.01em", "fontWeight": "600" }],
                        "metric-xl": ["40px", { "lineHeight": "48px", "letterSpacing": "0.02em", "fontWeight": "700" }],
                        "headline-lg-mobile": ["32px", { "lineHeight": "40px", "fontWeight": "600" }],
                        "display-xl": ["72px", { "lineHeight": "80px", "letterSpacing": "-0.02em", "fontWeight": "700" }],
                        "label-sm": ["12px", { "lineHeight": "16px", "letterSpacing": "0.05em", "fontWeight": "600" }]
                    }
                },
            },
        }
    </script>
<style>
        .glass-card {
            background: rgba(38, 50, 56, 0.6);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .text-gradient {
            background: linear-gradient(to right, #00daf3, #9cf0ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .btn-primary {
            background: linear-gradient(135deg, #00daf3, #00626e);
            transition: all 0.3s ease;
        }
        .btn-primary:hover {
            box-shadow: 0 0 15px rgba(0, 218, 243, 0.5);
        }
        .tab-active {
            background: rgba(0, 218, 243, 0.2);
            border: 1px solid #00daf3;
            color: #00daf3;
        }
        .tab-inactive {
            background: transparent;
            border: 1px solid transparent;
            color: #bac9cc;
        }
    </style>
</head>
<body class="bg-background text-on-background font-body-md overflow-x-hidden">
<!-- Top Navigation Bar -->
<nav class="bg-transparent backdrop-blur-md dark:bg-transparent border-b border-outline-variant/20 fixed top-0 w-full z-50">
<div class="flex justify-between items-center w-full px-margin-mobile md:px-margin-desktop py-4 max-w-container-max mx-auto">
<div class="font-headline-lg-mobile text-headline-lg-mobile font-bold text-primary dark:text-primary-fixed-dim">
                SmartWater HQ
            </div>
<div class="hidden md:flex items-center gap-6">
<a class="text-on-surface/80 hover:text-primary transition-colors font-body-md text-body-md hover:bg-white/10 dark:hover:bg-black/20 transition-all duration-300 px-3 py-2 rounded-md" href="#">首页</a>
<a class="text-primary font-bold border-b-2 border-primary pb-1 font-body-md text-body-md hover:bg-white/10 dark:hover:bg-black/20 transition-all duration-300 px-3 py-2 rounded-md" href="#">解决方案</a>
<a class="text-on-surface/80 hover:text-primary transition-colors font-body-md text-body-md hover:bg-white/10 dark:hover:bg-black/20 transition-all duration-300 px-3 py-2 rounded-md" href="#">产品中心</a>
<a class="text-on-surface/80 hover:text-primary transition-colors font-body-md text-body-md hover:bg-white/10 dark:hover:bg-black/20 transition-all duration-300 px-3 py-2 rounded-md" href="#">成功案例</a>
<a class="text-on-surface/80 hover:text-primary transition-colors font-body-md text-body-md hover:bg-white/10 dark:hover:bg-black/20 transition-all duration-300 px-3 py-2 rounded-md" href="#">新闻动态</a>
<a class="text-on-surface/80 hover:text-primary transition-colors font-body-md text-body-md hover:bg-white/10 dark:hover:bg-black/20 transition-all duration-300 px-3 py-2 rounded-md" href="#">关于我们</a>
<a class="text-on-surface/80 hover:text-primary transition-colors font-body-md text-body-md hover:bg-white/10 dark:hover:bg-black/20 transition-all duration-300 px-3 py-2 rounded-md" href="#">合作加盟</a>
</div>
<button class="btn-primary text-white font-bold py-2 px-6 rounded-full hover:scale-95 transition-transform font-body-md text-body-md">
                预约演示
            </button>
</div>
</nav>
<!-- Hero Section -->
<header class="relative pt-32 pb-20 px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto">
<div class="text-center max-w-4xl mx-auto space-y-6 relative z-10">
<h1 class="font-display-xl text-display-xl text-on-background">
                精准触达 <span class="text-gradient">核心痛点</span>
</h1>
<p class="font-headline-lg-mobile text-headline-lg-mobile text-on-surface-variant font-normal mt-4">
                "我们不做大而全的炫技，只解决您最关心的三件事：降电费、防罚款、管好人。"
            </p>
</div>
<!-- Abstract Background Element -->
<div class="absolute inset-0 z-0 overflow-hidden pointer-events-none opacity-30">
<div class="absolute top-1/4 left-1/4 w-96 h-96 bg-primary-container rounded-full mix-blend-screen filter blur-[100px] opacity-20"></div>
<div class="absolute bottom-1/4 right-1/4 w-[500px] h-[500px] bg-secondary-container rounded-full mix-blend-screen filter blur-[120px] opacity-20"></div>
</div>
</header>
<!-- Solutions Content -->
<main class="px-margin-mobile md:px-margin-desktop max-w-container-max mx-auto pb-32">
<!-- Sticky Tabs for Navigation (Desktop) -->
<div class="sticky top-20 z-40 bg-background/80 backdrop-blur-md py-4 mb-12 hidden md:flex justify-center gap-4 rounded-xl">
<button class="tab-active px-6 py-2 rounded-full font-label-sm text-label-sm uppercase tracking-wider transition-colors" onclick="scrollToSection('sec1')">运营管控大屏</button>
<button class="tab-inactive px-6 py-2 rounded-full font-label-sm text-label-sm uppercase tracking-wider transition-colors hover:bg-surface-variant/30" onclick="scrollToSection('sec2')">工艺优化</button>
<button class="tab-inactive px-6 py-2 rounded-full font-label-sm text-label-sm uppercase tracking-wider transition-colors hover:bg-surface-variant/30" onclick="scrollToSection('sec3')">设备资产</button>
<button class="tab-inactive px-6 py-2 rounded-full font-label-sm text-label-sm uppercase tracking-wider transition-colors hover:bg-surface-variant/30" onclick="scrollToSection('sec4')">安全环保</button>
<button class="tab-inactive px-6 py-2 rounded-full font-label-sm text-label-sm uppercase tracking-wider transition-colors hover:bg-surface-variant/30" onclick="scrollToSection('sec5')">智能工单</button>
</div>
<div class="space-y-32">
<!-- 1. 运营管控大屏 -->
<section class="scroll-mt-32" id="sec1">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter items-center">
<div class="md:col-span-5 space-y-6">
<div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-primary-fixed/10 text-primary-fixed border border-primary-fixed/20 mb-2">
<span class="material-symbols-outlined text-[16px]">dashboard</span>
<span class="font-label-sm text-label-sm">Managerial Oversight</span>
</div>
<h2 class="font-headline-lg text-headline-lg">运营管控大屏</h2>
<div class="space-y-4 text-on-surface-variant">
<p><strong>痛点:</strong> 数据孤岛，管理层无法实时掌握全局状态，决策滞后。</p>
<p><strong>方案:</strong> 整合全流程数据，提供直观的上帝视角。</p>
<p><strong>功能:</strong> 多维度关键指标(KPI)实时展示，预警中心，趋势预测。</p>
<p class="text-primary font-bold"><strong>价值:</strong> 决策效率提升40%，消除数据黑洞。</p>
</div>
<button class="mt-8 btn-primary text-white font-bold py-3 px-8 rounded-full flex items-center gap-2 w-fit">
<span>预约演示</span>
<span class="material-symbols-outlined text-[20px]">arrow_forward</span>
</button>
</div>
<div class="md:col-span-7 relative h-[400px]">
<div class="glass-card absolute inset-0 rounded-xl overflow-hidden p-4 flex flex-col">
<div class="flex-1 rounded-lg bg-surface-container-low border border-outline-variant/30 relative overflow-hidden" data-alt="A highly detailed dashboard interface for a water treatment plant command center, displayed on a glowing dark mode screen. The UI features complex graphs, real-time KPI metrics in neon cyan and blue, and a futuristic glassmorphism aesthetic. The layout is dense with data but immaculately structured, conveying authoritative clarity. Technical precision is evident in the typography and chart details. Rendered in a high-contrast corporate modern style." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuCnM74-x52er5tDpHZwFzBNRzrzARXPhPrJaB2LGZRCmJjw_7iRb5CrhaDxzSpOwA2PQnHhzhC2mgqGAEGCcVQtle7F_GQCRq4lFGddzN3YgK03mgoro1yv1_4Hx4OWIpnQr-1VLJD-aU5SYC7XW2rnwQdPBWnFlt7dI489XkUDSg_exmykkY3XNpWNeuXu4MkGC2d1YS6aD6ehkkOOjkhjYW-cJzJznJvpIJ33QApqnj65HpnQjzAA3Q')">
</div>
</div>
</div>
</div>
</section>
<!-- 2. 工艺优化与节能降耗 -->
<section class="scroll-mt-32" id="sec2">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter items-center">
<div class="md:col-span-7 order-2 md:order-1 relative h-[400px]">
<div class="glass-card absolute inset-0 rounded-xl overflow-hidden p-4 grid grid-cols-2 gap-4">
<div class="rounded-lg bg-surface-container-low border border-outline-variant/30 flex flex-col justify-center items-center p-6 relative overflow-hidden" data-alt="A close up UI mockup of a comparison graph showing power consumption before and after AI optimization. The dark mode graph uses vibrant cyan and blue gradients for the data lines. The 'after' line shows a dramatic drop in consumption. The background has a subtle blurred industrial aesthetic. It feels high-tech, precise, and professional." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuBx0VBEIcXkVOCl6Y4BqXjVYqAT0PWBLhqEqemdA7LWlqgD400XpHHsZUmfUgw1muUT7ZNYv9dmUTfsGD1sWgwJAOgLXnz-XO1MuygFXXUg5Eh--bxsCE95G0ITBeijwr4SnHnw3NHzgxu1j7J7FNYEYwYSY5f1svhcVGArC_RnhDc2o7-e_0AJcHw9jy9TDmz3bV1VmpiftRDpCNN0wyhOlPGj4R0EMxpujQcGW1IRGipYNSXaMWFB7A')">
</div>
<div class="rounded-lg bg-surface-container-low border border-outline-variant/30 flex flex-col justify-center items-center p-6 relative overflow-hidden" data-alt="A detailed UI card showing AI chemical dosing levels in a water treatment facility. The interface features a circular progress ring in vivid cyan and detailed technical readouts in a modern dark mode design. The glassmorphism card sits against a deeply blurred, dark industrial background. The mood is analytical and advanced." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuDP-tbedfu03ST4mnuliTjlTg8MxuRzYt-uGZgUdtZ91OIAgd6WspWZaVWd3dE3JMZVqzqDLYZ6pDw4JDJwObbS9aYAHdjO9kUZXdVUKuJESeKXNfMd0NOm-W3x0RNY9GU6kQaW4K2vIP6pqr7gF4-Zlc0EgFyNeegTo73QAYT5VXe98Y-HeE-lC_f9VGEW49OgslQVkW_fzK42kgFRwyHSFSVPeFtbIA5nMgmfpJG_HvDJ1dDudT9y9Q')">
</div>
</div>
</div>
<div class="md:col-span-5 space-y-6 order-1 md:order-2 md:pl-8">
<div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-secondary-fixed/10 text-secondary-fixed border border-secondary-fixed/20 mb-2">
<span class="material-symbols-outlined text-[16px]">energy_savings_leaf</span>
<span class="font-label-sm text-label-sm">AI Dosing &amp; Power Savings</span>
</div>
<h2 class="font-headline-lg text-headline-lg">工艺优化与节能降耗</h2>
<div class="space-y-4 text-on-surface-variant">
<p><strong>痛点:</strong> 能耗成本高昂，药剂投加凭经验，造成浪费。</p>
<p><strong>方案:</strong> 引入AI算法，实现精准投药与设备智能调度。</p>
<p><strong>功能:</strong> AI加药模型，风机水泵能效分析，动态控制策略。</p>
<p class="text-primary font-bold"><strong>价值:</strong> 综合能耗降低15%-25%，药剂成本节省20%。</p>
</div>
<button class="mt-8 btn-primary text-white font-bold py-3 px-8 rounded-full flex items-center gap-2 w-fit">
<span>预约演示</span>
<span class="material-symbols-outlined text-[20px]">arrow_forward</span>
</button>
</div>
</div>
</section>
<!-- 3. 设备资产管理 -->
<section class="scroll-mt-32" id="sec3">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter items-center">
<div class="md:col-span-5 space-y-6">
<div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-primary-fixed/10 text-primary-fixed border border-primary-fixed/20 mb-2">
<span class="material-symbols-outlined text-[16px]">build_circle</span>
<span class="font-label-sm text-label-sm">Asset Management</span>
</div>
<h2 class="font-headline-lg text-headline-lg">设备资产管理</h2>
<div class="space-y-4 text-on-surface-variant">
<p><strong>痛点:</strong> 设备台账混乱，巡检走过场，突发故障导致停机。</p>
<p><strong>方案:</strong> 一机一码，建立全生命周期健康档案。</p>
<p><strong>功能:</strong> 扫码巡检，预防性维护计划，自动报修预警，备件管理。</p>
<p class="text-primary font-bold"><strong>价值:</strong> 设备非计划停机率下降60%，延长核心资产寿命。</p>
</div>
<button class="mt-8 btn-primary text-white font-bold py-3 px-8 rounded-full flex items-center gap-2 w-fit">
<span>预约演示</span>
<span class="material-symbols-outlined text-[20px]">arrow_forward</span>
</button>
</div>
<div class="md:col-span-7 relative h-[400px]">
<div class="glass-card absolute inset-0 rounded-xl overflow-hidden p-4 flex gap-4">
<div class="w-1/3 rounded-lg bg-surface-container-low border border-outline-variant/30 flex flex-col justify-center items-center p-4 relative overflow-hidden" data-alt="A mobile app UI mockup for a worker scanning a QR code on an industrial water pump. The dark mode UI highlights a scanning viewfinder and automated alert notifications. The design uses semi-transparent layers and clean typography, emphasizing usability in a rugged environment. The aesthetic is corporate and modern." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuD_K_su2emCVbw2o6jCEGVlugkv7MLdqzVTmXwcf9FXOUlyNYDDkL4bOESdp7Q3S1P2LFHN6CJv9tx8rfbyTmCgllkwYYg5q-96C1Hs_7EfAQrUQxxZJRvDHlPhrk0UZCOQsd3fXXTafse-PzHYOhCIBWYaheSe7GPKDRH1fRNpaCGLnNIpt5DPdSs8UzCkZVvEcAvaggXBU4ornYmY4xStqoAAsXW-Dgbq0kjDZwqmyYq1nK1lTMrbeg')">
</div>
<div class="w-2/3 rounded-lg bg-surface-container-low border border-outline-variant/30 relative overflow-hidden" data-alt="A desktop UI dashboard showing a detailed asset health overview. A 3D model of a massive industrial water filter is central, surrounded by health metrics and alert status indicators in dark mode with cyan accents. The glassmorphism card creates depth against a deep navy canvas. The visual communicates authoritative technical monitoring." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuDnZ0h2gxmMyLk6Waep9aG3Q0WH3Wij9t1CrBHF1rVwBUHjIzlgFWoWrcb1Y6s5VjDA7X3-ZUMSwmlOihD8TWOGMjrUh0lRe2D469pDGWEzgQHjOqsOg9n_p4zk3PWvVBIpt8hbOVBtrChloDjwTHvl5NcegEyqmGLGzSvH_GZ3k5uIjZMv32louyz-sb0n3apatzaOdX4JKRuNcuOQjUPV2pZuPZyqd_lk0sm7_sFHe4O-RUNuYhFO4Q')">
</div>
</div>
</div>
</div>
</section>
<!-- 4. 安全环保合规 -->
<section class="scroll-mt-32" id="sec4">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter items-center">
<div class="md:col-span-7 order-2 md:order-1 relative h-[400px]">
<div class="glass-card absolute inset-0 rounded-xl overflow-hidden p-4 flex flex-col">
<div class="flex-1 rounded-lg bg-surface-container-low border border-outline-variant/30 relative overflow-hidden" data-alt="A highly structured interface displaying hazardous waste tracking and compliance data for an industrial plant. The dark mode screen utilizes strict grid layouts, sharp typography, and status indicators in success green and warning yellow. The design incorporates a subtle glassmorphism effect, ensuring critical safety data is presented with utmost clarity and authority." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuC2vemPLvagc-IjiJkDXL3D-yhj_nunfgNbou6-mSxQrpbOQSx870GHQ2KrsntgDIywOvpPqDj2Zwl5VoIro4fTv1aYIkp3CZaQ3kFDzCJHwPVtEaq2LhOb_LJR5_gNN685--w2HQ49kKgI8IKs4HlLDZxpWBDnCGInonuE8Vb39JR1H7ixziOC-zi79HnM9IMFMzamXR7r6dRZl0eh3AAM5ANUU4qmJOO0JGB1-EQglbJ17F0JKWcMXg')">
</div>
</div>
</div>
<div class="md:col-span-5 space-y-6 order-1 md:order-2 md:pl-8">
<div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-secondary-fixed/10 text-secondary-fixed border border-secondary-fixed/20 mb-2">
<span class="material-symbols-outlined text-[16px]">health_and_safety</span>
<span class="font-label-sm text-label-sm">Compliance &amp; Safety</span>
</div>
<h2 class="font-headline-lg text-headline-lg">安全环保合规</h2>
<div class="space-y-4 text-on-surface-variant">
<p><strong>痛点:</strong> 环保数据造假风险，危废处理不规范面临巨额罚款。</p>
<p><strong>方案:</strong> 建立防篡改的环保台账与标准化安全流程体系。</p>
<p><strong>功能:</strong> 危废全流程追踪，出水水质超标自动熔断，安全知识库培训。</p>
<p class="text-primary font-bold"><strong>价值:</strong> 杜绝环保罚单，实现100%合规运营。</p>
</div>
<button class="mt-8 btn-primary text-white font-bold py-3 px-8 rounded-full flex items-center gap-2 w-fit">
<span>预约演示</span>
<span class="material-symbols-outlined text-[20px]">arrow_forward</span>
</button>
</div>
</div>
</section>
<!-- 5. 智能工单调度 -->
<section class="scroll-mt-32" id="sec5">
<div class="grid grid-cols-1 md:grid-cols-12 gap-gutter items-center">
<div class="md:col-span-5 space-y-6">
<div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-primary-fixed/10 text-primary-fixed border border-primary-fixed/20 mb-2">
<span class="material-symbols-outlined text-[16px]">assignment_turned_in</span>
<span class="font-label-sm text-label-sm">Smart Dispatch</span>
</div>
<h2 class="font-headline-lg text-headline-lg">智能工单调度</h2>
<div class="space-y-4 text-on-surface-variant">
<p><strong>痛点:</strong> 任务分配靠吼，过程无记录，人员绩效难以量化考核。</p>
<p><strong>方案:</strong> 数字化流转，实现"事找人"的闭环管理。</p>
<p><strong>功能:</strong> 告警自动转工单，SLA超时升级，维修过程实时记录，员工绩效看板。</p>
<p class="text-primary font-bold"><strong>价值:</strong> 现场人员人效提升30%，权责清晰无推诿。</p>
</div>
<button class="mt-8 btn-primary text-white font-bold py-3 px-8 rounded-full flex items-center gap-2 w-fit">
<span>预约演示</span>
<span class="material-symbols-outlined text-[20px]">arrow_forward</span>
</button>
</div>
<div class="md:col-span-7 relative h-[400px]">
<div class="glass-card absolute inset-0 rounded-xl overflow-hidden p-4 grid grid-cols-1 md:grid-cols-2 gap-4">
<div class="rounded-lg bg-surface-container-low border border-outline-variant/30 relative overflow-hidden" data-alt="A Kanban-style UI board for automated dispatch tracking in a dark mode industrial application. Tasks are represented as sleek cards with cyan progress bars and worker avatars. The glassmorphism panels rest on a deep navy background. The layout is optimized for quick status recognition, reflecting a highly efficient, modern operational workflow." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuAZDt8uOMnvMZhkIpOl8w2T_WCrf4tlpiThoq-UKgP_RQeQ2ttCRt72Vf-7XS9XehZfGiZ_GG_el44I32Fr0VGXNT41andB8f1IixlosxSdHx3t7-sBbe_rh_WJlO46glFerV2KQSCk58RxvD5m782TM3o7y_WHk3qDq2Xk-nBfo0I2ODQaklJbdecdqa-SBsxwNE-mc6tDc1v_7NWmc571X91Et5F6jgj_jc-8qaw5_T6Z7Zjo224m5w')">
</div>
<div class="rounded-lg bg-surface-container-low border border-outline-variant/30 relative overflow-hidden" data-alt="A performance tracking dashboard UI displaying a worker's efficiency metrics. The dark interface features vibrant radial charts and a performance score in bright cyan text. The design utilizes semi-transparent layers and clean, sans-serif typography to communicate actionable intelligence clearly within a corporate technological context." style="background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuB6rPS7xie9VXshGRtdRK4pa2lvYTkw33gt8OHmu84CTGbgr32cM6Voc0YOWDWX5DtgppWkYXzHeO_8qVCTJIjFdc5bPRGfSWyNqpXsZOxg_7XjVn9q9lrfUSCrM3hARG3fqOUPx19TSOwZqIh8Z_pHHbINEbuMYmYk9JmtORedpnfurjIXgcfqfg1nUH5QKM_QDG_BIfprI0_Rl7fD27USSqb5nzwjdqtNCfGbb53FWVpT_73eO0rKFg')">
</div>
</div>
</div>
</div>
</section>
</div>
</main>
<!-- Footer -->
<footer class="bg-surface-container-lowest dark:bg-background border-t border-outline-variant/10 w-full relative bottom-0 mt-20">
<div class="grid grid-cols-1 md:grid-cols-4 gap-gutter px-margin-desktop py-stack-lg max-w-container-max mx-auto">
<div class="col-span-1 md:col-span-2">
<div class="font-headline-lg text-headline-lg text-primary mb-4">SmartWater HQ</div>
<p class="text-on-surface-variant font-body-md text-body-md max-w-md">
                    Industrial Excellence in water management and sewage treatment.
                </p>
</div>
<div>
<h4 class="font-label-sm text-label-sm text-on-surface mb-4 uppercase tracking-wider">Links</h4>
<div class="flex flex-col gap-2">
<a class="text-on-surface-variant hover:text-primary transition-opacity font-body-md text-body-md" href="#">首页</a>
<a class="text-on-surface-variant hover:text-primary transition-opacity font-body-md text-body-md" href="#">解决方案</a>
<a class="text-on-surface-variant hover:text-primary transition-opacity font-body-md text-body-md" href="#">产品中心</a>
</div>
</div>
<div>
<h4 class="font-label-sm text-label-sm text-on-surface mb-4 uppercase tracking-wider">Legal</h4>
<div class="flex flex-col gap-2">
<a class="text-on-surface-variant hover:text-primary transition-opacity font-body-md text-body-md" href="#">关于我们</a>
<a class="text-on-surface-variant hover:text-primary transition-opacity font-body-md text-body-md" href="#">加入我们</a>
<a class="text-on-surface-variant hover:text-primary transition-opacity font-body-md text-body-md" href="#">联系我们</a>
<a class="text-on-surface-variant hover:text-primary transition-opacity font-body-md text-body-md" href="#">隐私政策</a>
</div>
</div>
</div>
<div class="border-t border-outline-variant/10 py-6 text-center text-on-surface-variant font-body-md text-body-md">
            © 2024 Smart Water Management Systems. All rights reserved.
        </div>
</footer>
<script>
        function scrollToSection(id) {
            document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
            
            // Basic tab highlighting logic for demonstration
            const tabs = document.querySelectorAll('.sticky button');
            tabs.forEach(tab => {
                tab.classList.remove('tab-active');
                tab.classList.add('tab-inactive');
            });
            event.currentTarget.classList.remove('tab-inactive');
            event.currentTarget.classList.add('tab-active');
        }
    </script>
</body></html>

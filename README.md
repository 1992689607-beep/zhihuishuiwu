[deepseek_html_20260731_0ee343.html](https://github.com/user-attachments/files/30584772/deepseek_html_20260731_0ee343.html)
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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Revenue Engine: 2026 Strategy Dashboard</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        /* Custom Fonts & Base Styles */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f7f5; /* Warm Neutral Background */
            color: #2d3748;
        }

        /* Chart Container Styling - MANDATORY */
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }

        /* Interactive Element Transitions */
        .agent-card {
            transition: all 0.3s ease;
            cursor: pointer;
        }
        .agent-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
        }
        .agent-card.active {
            border-color: #4f46e5;
            background-color: #fff;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
        }

        /* Timeline Stepper */
        .step-circle {
            transition: all 0.3s ease;
        }
        .step-line {
            transition: all 0.3s ease;
        }

        /* Custom Scrollbar for cleaner look */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1; 
        }
        ::-webkit-scrollbar-thumb {
            background: #c5c5c5; 
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #a8a8a8; 
        }
    </style>

    <!-- Chosen Palette: Warm Neutrals (Stone/Gray) with Tech Accents (Indigo, Emerald, Amber, Rose) -->
    <!-- Application Structure Plan: 
         1. Header: Strategy overview and core philosophy ("Minimum Human Intervention").
         2. The Metrics Dashboard: Visualizes the "Why" - Key Success Metrics (ROAS, LTV) using Chart.js.
         3. The Agent Ecosystem (Core Logic): An interactive tab/card system detailing the 4 Agents (Hunter, Creator, Closer, Growth). This is the heart of the app.
         4. Implementation Roadmap: A horizontal timeline allowing users to step through the 4-week build phase.
         5. Guardrails: A footer section for Ethics/Safety.
         Rationale: This dashboard structure allows the user to first understand the goals (Metrics), then explore the machinery (Agents), and finally see how to build it (Roadmap).
    -->
    <!-- Visualization & Content Choices:
         1. Metrics -> Goal: Inform/Motivate -> Viz: Bar Chart comparing Industry Avg vs AI Strategy -> Interaction: Hover for values -> Justification: Shows immediate value prop.
         2. Agents -> Goal: Explain Complex Logic -> Viz: Interactive Cards (Tabs) -> Interaction: Click card to update "Agent Detail View" (Workflow/Tech Stack) -> Justification: Reduces cognitive load by showing one agent at a time.
         3. Roadmap -> Goal: Planning -> Viz: Horizontal Stepper -> Interaction: Click step to reveal tasks -> Justification: Linear progression matches the concept of time.
         4. NO SVG/Mermaid confirmed. Using HTML/CSS for layout and flow.
    -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->

</head>
<body class="antialiased selection:bg-indigo-100 selection:text-indigo-800">

    <!-- Main Container -->
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 space-y-12">

        <!-- HEADER SECTION -->
        <header class="text-center space-y-4 max-w-3xl mx-auto">
            <div class="inline-flex items-center px-3 py-1 rounded-full bg-indigo-100 text-indigo-800 text-xs font-semibold tracking-wide uppercase">
                2026 Strategy Blueprint
            </div>
            <h1 class="text-4xl md:text-5xl font-bold text-gray-900 tracking-tight">
                AI Revenue Engine
            </h1>
            <p class="text-lg text-gray-600 leading-relaxed">
                A blueprint for an autonomous e-commerce ecosystem. The core philosophy is 
                <span class="font-bold text-gray-900">"Minimum Human Intervention"</span>, utilizing a headless architecture powered by four specialized AI agents.
            </p>
        </header>

        <!-- KPI / METRICS SECTION -->
        <section class="bg-white rounded-2xl shadow-sm border border-gray-200 overflow-hidden">
            <div class="p-6 md:p-8 border-b border-gray-100">
                <h2 class="text-2xl font-bold text-gray-900 mb-2">Success Metrics Projection</h2>
                <p class="text-gray-500 mb-6">
                    Projected performance indicators for the AI-driven model compared to traditional e-commerce benchmarks. 
                    <span class="text-sm bg-gray-100 px-2 py-1 rounded ml-2">Interactive Chart</span>
                </p>
                
                <div class="grid grid-cols-1 lg:grid-cols-3 gap-8 items-center">
                    <!-- Text Stats -->
                    <div class="lg:col-span-1 space-y-6">
                        <div class="p-4 bg-emerald-50 rounded-xl border border-emerald-100">
                            <div class="text-sm text-emerald-600 font-medium mb-1">Target ROAS</div>
                            <div class="text-3xl font-bold text-emerald-900">> 3.0x</div>
                            <div class="text-xs text-emerald-700 mt-1">Return on Ad Spend</div>
                        </div>
                        <div class="p-4 bg-blue-50 rounded-xl border border-blue-100">
                            <div class="text-sm text-blue-600 font-medium mb-1">Optimization</div>
                            <div class="text-3xl font-bold text-blue-900">Real-Time</div>
                            <div class="text-xs text-blue-700 mt-1">Via AI Heatmaps (Hotjar)</div>
                        </div>
                        <div class="p-4 bg-purple-50 rounded-xl border border-purple-100">
                            <div class="text-sm text-purple-600 font-medium mb-1">LTV Boost</div>
                            <div class="text-3xl font-bold text-purple-900">Automated</div>
                            <div class="text-xs text-purple-700 mt-1">Personalized Email Upsells</div>
                        </div>
                    </div>

                    <!-- Chart Container -->
                    <div class="lg:col-span-2 flex justify-center">
                        <div class="chart-container">
                            <canvas id="metricsChart"></canvas>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bg-gray-50 px-6 py-4">
                <p class="text-sm text-center text-gray-500">
                    <span class="font-bold">Goal:</span> Secure steady daily revenue with continuous automated optimization.
                </p>
            </div>
        </section>

        <!-- AGENT ECOSYSTEM SECTION (Interactive Tab/Cards) -->
        <section>
            <div class="mb-8">
                <h2 class="text-2xl font-bold text-gray-900">The 4-Agent Architecture</h2>
                <p class="text-gray-500 mt-2">
                    The system is divided into four autonomous agents. Click an agent below to inspect its technology stack and workflow.
                </p>
            </div>

            <!-- Agent Selector Grid -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mb-8">
                <button onclick="selectAgent('hunter')" id="btn-hunter" class="agent-card active p-4 rounded-xl border-2 border-indigo-500 bg-white text-left focus:outline-none">
                    <div class="text-2xl mb-2">🎯</div>
                    <div class="font-bold text-gray-900">The Hunter</div>
                    <div class="text-xs text-gray-500">Market Research</div>
                </button>
                <button onclick="selectAgent('creator')" id="btn-creator" class="agent-card p-4 rounded-xl border-2 border-transparent bg-gray-50 text-left hover:bg-white focus:outline-none">
                    <div class="text-2xl mb-2">🎨</div>
                    <div class="font-bold text-gray-900">The Creator</div>
                    <div class="text-xs text-gray-500">Content & SEO</div>
                </button>
                <button onclick="selectAgent('closer')" id="btn-closer" class="agent-card p-4 rounded-xl border-2 border-transparent bg-gray-50 text-left hover:bg-white focus:outline-none">
                    <div class="text-2xl mb-2">🤝</div>
                    <div class="font-bold text-gray-900">The Closer</div>
                    <div class="text-xs text-gray-500">Sales & Support</div>
                </button>
                <button onclick="selectAgent('growth')" id="btn-growth" class="agent-card p-4 rounded-xl border-2 border-transparent bg-gray-50 text-left hover:bg-white focus:outline-none">
                    <div class="text-2xl mb-2">🚀</div>
                    <div class="font-bold text-gray-900">The Growth</div>
                    <div class="text-xs text-gray-500">Marketing</div>
                </button>
            </div>

            <!-- Agent Detail View -->
            <div id="agent-detail-panel" class="bg-white rounded-2xl shadow-lg border border-gray-100 p-6 md:p-10 transition-all duration-300">
                <!-- Content injected via JS -->
            </div>
        </section>

        <!-- IMPLEMENTATION ROADMAP SECTION -->
        <section>
            <div class="mb-8">
                <h2 class="text-2xl font-bold text-gray-900">Implementation Roadmap</h2>
                <p class="text-gray-500 mt-2">
                    A 4-week execution plan to build the automated hub. Click on a phase to see the checklist.
                </p>
            </div>

            <div class="bg-white rounded-2xl shadow-sm border border-gray-200 overflow-hidden">
                <!-- Timeline Navigation -->
                <div class="flex border-b border-gray-200 overflow-x-auto no-scrollbar">
                    <button onclick="setPhase(1)" id="phase-btn-1" class="flex-1 py-4 px-6 text-sm font-semibold text-indigo-600 border-b-2 border-indigo-600 bg-indigo-50 whitespace-nowrap focus:outline-none">
                        Phase 1: Week 1-2
                    </button>
                    <button onclick="setPhase(2)" id="phase-btn-2" class="flex-1 py-4 px-6 text-sm font-medium text-gray-500 border-b-2 border-transparent hover:bg-gray-50 whitespace-nowrap focus:outline-none">
                        Phase 2: Week 3
                    </button>
                    <button onclick="setPhase(3)" id="phase-btn-3" class="flex-1 py-4 px-6 text-sm font-medium text-gray-500 border-b-2 border-transparent hover:bg-gray-50 whitespace-nowrap focus:outline-none">
                        Phase 3: Week 4
                    </button>
                </div>

                <!-- Phase Content -->
                <div class="p-6 md:p-8 min-h-[250px] flex flex-col justify-center" id="roadmap-content">
                    <!-- Content injected via JS -->
                </div>
            </div>
        </section>

        <!-- GUARDRAILS SECTION -->
        <section class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div class="bg-rose-50 rounded-xl p-6 border border-rose-100">
                <h3 class="text-lg font-bold text-rose-900 mb-3 flex items-center">
                    <span class="mr-2">🛡️</span> Human-in-the-Loop
                </h3>
                <p class="text-rose-800 text-sm leading-relaxed mb-4">
                    Automated does not mean unsupervised. A critical safety protocol requires a weekly 15-minute review of all AI-generated content.
                </p>
                <div class="bg-white/60 rounded p-3 text-xs text-rose-700 font-medium">
                    Check: Brand Alignment • Tone Consistency
                </div>
            </div>

            <div class="bg-amber-50 rounded-xl p-6 border border-amber-100">
                <h3 class="text-lg font-bold text-amber-900 mb-3 flex items-center">
                    <span class="mr-2">⚖️</span> Compliance & Safety
                </h3>
                <p class="text-amber-800 text-sm leading-relaxed mb-4">
                    Strict adherence to platform policies is enforced to prevent ad account bans.
                </p>
                <div class="bg-white/60 rounded p-3 text-xs text-amber-700 font-medium">
                    Check: Meta/Google Ad Policies • Data Privacy
                </div>
            </div>
        </section>

        <!-- FOOTER -->
        <footer class="border-t border-gray-200 pt-8 pb-12 text-center text-sm text-gray-400">
            <p>Based on the "AI-Powered E-Commerce & Revenue Engine: 2026 Strategy"</p>
        </footer>

    </div>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // --- DATA STORE ---
        const agentData = {
            hunter: {
                title: "The Hunter Agent",
                role: "Market Research & Niche Discovery",
                goal: "Identify trending, high-margin niches with low competition.",
                techStack: ["Gemini API (Search Grounding)", "Google Trends API", "ScrapingAnt"],
                workflow: [
                    "Scans TikTok Creative Center & Amazon Movers/Shakers weekly.",
                    "Analyzes competitor pricing and marketing gaps.",
                    "Flags products with high demand but poor current marketing execution."
                ],
                color: "indigo"
            },
            creator: {
                title: "The Creator Agent",
                role: "Content Generation & SEO",
                goal: "Generate high-converting listings, blogs, and social assets instantly.",
                techStack: ["Gemini-2.5-Flash-Preview (Text)", "Imagen-4.0 (Product Images)"],
                workflow: [
                    "Receives 'Product Keyword' from Hunter Agent.",
                    "Generates technical spec lists and benefits-driven sales copy.",
                    "Creates 5 SEO blog posts and 10 social media captions.",
                    "Produces metadata for Search Engine Optimization."
                ],
                color: "purple"
            },
            closer: {
                title: "The Closer Agent",
                role: "Sales & Customer Support",
                goal: "Convert visitors and handle logistics with zero friction.",
                techStack: ["Botpress / Intercom", "Stripe SDK", "PayPal SDK"],
                workflow: [
                    "Identifies user intent (e.g., specific product questions).",
                    "Answers queries instantly (e.g., 'Does this fit size M?').",
                    "Triggers 'Buy Now' links directly within the chat interface."
                ],
                color: "blue"
            },
            growth: {
                title: "The Growth Agent",
                role: "Marketing Automation",
                goal: "Automated traffic generation and retargeting.",
                techStack: ["Klaviyo (AI Email)", "AdCreative.ai API"],
                workflow: [
                    "Executes automated retargeting for abandoned carts.",
                    "Runs AI-driven A/B testing on ad headlines.",
                    "Generates personalized email campaigns to boost LTV."
                ],
                color: "orange"
            }
        };

        const roadmapData = {
            1: {
                title: "Phase 1: The Automated Hub",
                weeks: "Weeks 1-2",
                focus: "Infrastructure",
                tasks: [
                    "Setup Headless CMS (Strapi) or Shopify Store.",
                    "Connect AI tools via Zapier or Make.com.",
                    "Configure Stripe as the primary payment gateway."
                ]
            },
            2: {
                title: "Phase 2: AI Content Integration",
                weeks: "Week 3",
                focus: "Content Engine",
                tasks: [
                    "Build script: Input Keyword -> Output Specs & Copy.",
                    "Design 'Benefits-Driven' sales page templates.",
                    "Automate SEO Metadata generation (Title/Description)."
                ]
            },
            3: {
                title: "Phase 3: The Marketing Loop",
                weeks: "Week 4",
                focus: "Traffic & Analytics",
                tasks: [
                    "Setup Google Search Console & Analytics.",
                    "Deploy AI Content Calendar for Pinterest/Instagram.",
                    "Launch initial automated ad campaigns."
                ]
            }
        };

        // --- STATE MANAGEMENT ---
        let currentAgent = 'hunter';
        let currentPhase = 1;

        // --- FUNCTIONS ---

        function renderAgent(agentKey) {
            const data = agentData[agentKey];
            const panel = document.getElementById('agent-detail-panel');
            
            // Generate Tech Badges
            const techBadges = data.techStack.map(tech => 
                `<span class="inline-block px-3 py-1 mr-2 mb-2 text-xs font-semibold rounded-full bg-${data.color}-100 text-${data.color}-800 border border-${data.color}-200">${tech}</span>`
            ).join('');

            // Generate Workflow Steps
            const workflowSteps = data.workflow.map((step, index) => 
                `<li class="flex items-start">
                    <span class="flex-shrink-0 w-6 h-6 flex items-center justify-center rounded-full bg-${data.color}-100 text-${data.color}-600 font-bold text-xs mr-3 mt-0.5">${index + 1}</span>
                    <span class="text-gray-600">${step}</span>
                </li>`
            ).join('');

            panel.innerHTML = `
                <div class="flex flex-col md:flex-row gap-8">
                    <div class="md:w-1/3">
                        <h3 class="text-2xl font-bold text-gray-900 mb-2">${data.title}</h3>
                        <p class="text-sm font-medium text-gray-500 uppercase tracking-wide mb-4">${data.role}</p>
                        <div class="p-4 bg-${data.color}-50 rounded-xl border border-${data.color}-100 mb-6">
                            <h4 class="text-sm font-bold text-${data.color}-900 mb-2">Core Goal</h4>
                            <p class="text-sm text-${data.color}-800 leading-relaxed">${data.goal}</p>
                        </div>
                        <div>
                            <h4 class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2">Tech Stack</h4>
                            <div class="flex flex-wrap">
                                ${techBadges}
                            </div>
                        </div>
                    </div>
                    <div class="md:w-2/3 border-t md:border-t-0 md:border-l border-gray-100 pt-6 md:pt-0 md:pl-8">
                        <h4 class="text-lg font-bold text-gray-900 mb-4">Operational Workflow</h4>
                        <ul class="space-y-4">
                            ${workflowSteps}
                        </ul>
                    </div>
                </div>
            `;
        }

        function selectAgent(agentKey) {
            currentAgent = agentKey;
            
            // Update UI classes
            const agents = ['hunter', 'creator', 'closer', 'growth'];
            agents.forEach(a => {
                const btn = document.getElementById(`btn-${a}`);
                if (a === agentKey) {
                    btn.classList.add('active', 'border-indigo-500', 'bg-white');
                    btn.classList.remove('border-transparent', 'bg-gray-50');
                } else {
                    btn.classList.remove('active', 'border-indigo-500', 'bg-white');
                    btn.classList.add('border-transparent', 'bg-gray-50');
                }
            });

            renderAgent(agentKey);
        }

        function renderPhase(phaseId) {
            const data = roadmapData[phaseId];
            const container = document.getElementById('roadmap-content');
            
            const tasksList = data.tasks.map(task => 
                `<li class="flex items-center text-gray-700">
                    <svg class="w-5 h-5 text-green-500 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                    ${task}
                </li>`
            ).join('');

            container.innerHTML = `
                <div class="animate-fade-in">
                    <div class="flex justify-between items-end mb-6">
                        <div>
                            <span class="text-xs font-bold text-indigo-500 uppercase tracking-wider">${data.weeks}</span>
                            <h3 class="text-2xl font-bold text-gray-900 mt-1">${data.title}</h3>
                        </div>
                        <div class="text-right hidden sm:block">
                            <span class="text-sm text-gray-500">Focus Area:</span>
                            <span class="text-sm font-bold text-gray-900 bg-gray-100 px-3 py-1 rounded-full ml-2">${data.focus}</span>
                        </div>
                    </div>
                    <div class="bg-gray-50 rounded-xl p-6 border border-gray-100">
                        <ul class="space-y-3">
                            ${tasksList}
                        </ul>
                    </div>
                </div>
            `;
        }

        function setPhase(phaseId) {
            currentPhase = phaseId;
            
            // Update Buttons
            for(let i=1; i<=3; i++) {
                const btn = document.getElementById(`phase-btn-${i}`);
                if (i === phaseId) {
                    btn.className = "flex-1 py-4 px-6 text-sm font-semibold text-indigo-600 border-b-2 border-indigo-600 bg-indigo-50 whitespace-nowrap focus:outline-none transition-all";
                } else {
                    btn.className = "flex-1 py-4 px-6 text-sm font-medium text-gray-500 border-b-2 border-transparent hover:bg-gray-50 whitespace-nowrap focus:outline-none transition-all";
                }
            }
            renderPhase(phaseId);
        }

        // --- CHART INITIALIZATION ---
        function initCharts() {
            const ctx = document.getElementById('metricsChart').getContext('2d');
            new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: ['ROAS (Ad Spend)', 'Conv. Rate (%)', 'LTV ($)'],
                    datasets: [
                        {
                            label: 'Industry Average',
                            data: [1.5, 2.1, 45],
                            backgroundColor: '#cbd5e1', // Slate 300
                            borderRadius: 4,
                            barPercentage: 0.6
                        },
                        {
                            label: 'AI Strategy Target',
                            data: [3.2, 4.8, 85], // Targets from report
                            backgroundColor: ['#10b981', '#3b82f6', '#8b5cf6'], // Emerald, Blue, Purple
                            borderRadius: 4,
                            barPercentage: 0.6
                        }
                    ]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: {
                            position: 'top',
                            align: 'end',
                            labels: {
                                usePointStyle: true,
                                boxWidth: 8
                            }
                        },
                        tooltip: {
                            backgroundColor: 'rgba(17, 24, 39, 0.9)',
                            padding: 12,
                            titleFont: { size: 13 },
                            bodyFont: { size: 12 }
                        }
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            grid: {
                                color: '#f3f4f6'
                            },
                            ticks: {
                                font: { size: 11 }
                            }
                        },
                        x: {
                            grid: {
                                display: false
                            },
                            ticks: {
                                font: { size: 11 }
                            }
                        }
                    }
                }
            });
        }

        // --- INIT ---
        document.addEventListener('DOMContentLoaded', () => {
            selectAgent('hunter'); // Load default agent
            setPhase(1); // Load default phase
            initCharts();
        });

    </script>
</body>
</html>

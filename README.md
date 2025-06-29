<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AUTOMATE ACADEMY — AI Automation Career Programs</title>
    <!-- Favicon -->
    <link rel="icon" type="image/png" href="file:///C:/Users/hp/Desktop/Automate%20Academy/936f1788-2669-48f5-a8b5-85a93c432a1b.png">
    <style>
        /* AUDIENCE SECTION STYLES */
.audience-section {
    margin: 60px 0;
    text-align: center; /* Center align all text */
}

.audience-cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 30px;
    justify-content: center; /* Center cards horizontally */
}

.audience-card {
    flex: 1 1 300px;
    background: var(--white);
    border-radius: 8px;
    padding: 25px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    text-align: left; /* Keep content left-aligned inside cards */
    max-width: 350px; /* Optional: limit card width */
}

/* Rest of your existing audience styles remain the same */
.audience-card h3 {
    color: var(--primary-blue);
    margin-bottom: 15px;
    font-size: 20px;
}

.audience-list {
    list-style: none;
}

.audience-list li {
    margin-bottom: 10px;
    padding-left: 25px;
    position: relative;
}

.audience-list li:before {
    content: "→";
    color: var(--primary-blue);
    position: absolute;
    left: 0;
}

@media (max-width: 768px) {
    .audience-card {
        flex: 1 1 100%;
    }
}
        /* DISCOUNT SECTION STYLES */
.discount-section {
    margin: 60px auto;
    text-align: center;
}

.discount-card {
    background-color: var(--gray);
    border-radius: 8px;
    padding: 30px;
    box-shadow: 0 5px 15px rgba(187, 187, 187, 0.05);
    display: flex;
    align-items: center;
    max-width: 500px;
    margin: 20px auto;
    text-align: left;
}

.discount-icon {
    font-size: 40px;
    margin-right: 25px;
    color: var(--primary-blue);
}

.discount-content h3 {
    color: var(--dark-blue);
    margin-bottom: 10px;
    font-size: 20px;
}


.discount-content p {
    color: var(--dark-gray);
    margin-bottom: 15px;
}

.discount-button {
    display: inline-block;
    background-color: var(--primary-blue);
    color: white;
    padding: 10px 20px;
    border-radius: 4px;
    text-decoration: none;
    font-weight: 600;
    transition: background-color 0.3s;
    align-items: center;
}

.discount-button:hover {
    background-color: var(--dark-blue);
}

@media (max-width: 600px) {
    .discount-card {
        flex-direction: column;
        text-align: center;

    }
    
    .discount-icon {
        margin-right: 0;
        margin-bottom: 15px;
    }
}
        :root {
            --primary-blue: #1a73e8;
            --dark-blue: #0d47a1;
            --light-blue: #e8f0fe;
            --white: #ffffff;
            --gray: #f5f5f5;
            --dark-gray: #5f6368;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: #333;
            background-color: var(--white);
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background-color: var(--white);
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 100;
            text-align: center; 
        }
        
        .logo {
            font-size: 24px;
            font-weight: 700;
            color: var(--primary-blue);
        }
        
        /* ===== HERO SECTION ===== */
        .hero {
            text-align: center;
            padding: 80px 0;
            background: linear-gradient(135deg, var(--light-blue) 0%, var(--white) 100%);
            position: relative;
            overflow: hidden;
        }
        
        .hero::after {
            content: "";
            position: absolute;
            bottom: 0;
            right: 0;
            width: 300px;
            height: 300px;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><path fill="%231a73e8" fill-opacity="0.05" d="M20,20 L80,20 L80,80 L20,80 Z M30,30 L70,30 L70,70 L30,70 Z M40,40 L60,40 L60,60 L40,60 Z"/></svg>') no-repeat;
            background-size: contain;
            opacity: 0.3;
        }
        
        .hero h1 {
            font-size: 42px;
            margin-bottom: 20px;
            color: var(--dark-blue);
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .hero p {
            font-size: 20px;
            color: var(--dark-gray);
            max-width: 600px;
            margin: 0 auto 30px;
        }
        
        .button-group {
            display: flex;
            gap: 15px;
            justify-content: center;
            flex-wrap: wrap;
        }
        
        .button-primary, .button-secondary {
            display: inline-block;
            padding: 15px 30px;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        
        .button-primary {
            background-color: var(--primary-blue);
            color: var(--white);
        }
        
        .button-primary:hover {
            background-color: var(--dark-blue);
            transform: translateY(-2px);
        }
        
        .button-secondary {
            background-color: var(--white);
            color: var(--primary-blue);
            border: 2px solid var(--primary-blue);
        }
        
        .button-secondary:hover {
            background-color: var(--light-blue);
            transform: translateY(-2px);
        }
        
        /* ===== PROGRAM CARDS ===== */
        .section-title {
            text-align: center;
            margin: 60px 0 40px;
            color: var(--dark-blue);
        }
        
        .programs {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            margin: 40px 0;
            justify-content: center;
        }
        
        .program-card {
            flex: 1 1 300px;
            background: var(--white);
            border: 1px solid #e0e0e0;
            border-radius: 8px;
            padding: 30px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s ease;
            max-width: 350px;
        }
        
        .program-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        
        .program-card h3 {
            font-size: 22px;
            margin-bottom: 15px;
            color: var(--dark-blue);
        }
        
        .program-meta {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            font-weight: 600;
        }
        
        .program-price {
            color: var(--primary-blue);
        }
        
        .program-duration {
            color: var(--dark-gray);
        }
        
        .program-features {
            list-style: none;
            margin: 20px 0;
        }
        
        .program-features li {
            margin-bottom: 12px;
            position: relative;
            padding-left: 25px;
        }
        
        .program-features li:before {
            content: "•";
            color: var(--primary-blue);
            position: absolute;
            left: 10px;
            font-weight: bold;
        }
        
        .program-audience {
            margin-top: 20px;
            padding-top: 15px;
            border-top: 1px solid #eee;
            font-style: italic;
            color: var(--dark-gray);
        }
        
        .program-button {
            display: block;
            text-align: center;
            margin-top: 20px;
            padding: 12px;
            background-color: var(--primary-blue);
            color: white;
            border-radius: 4px;
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.3s ease;
        }
        
        .program-button:hover {
            background-color: var(--dark-blue);
        }
        
        /* ===== TABBED CONTENT ===== */
        .tabs {
            display: flex;
            border-bottom: 1px solid #ddd;
            margin: 40px 0 20px;
        }
        
        .tab-button {
            padding: 12px 20px;
            background: none;
            border: none;
            cursor: pointer;
            font-size: 16px;
            font-weight: 600;
            color: var(--dark-gray);
            position: relative;
        }
        
        .tab-button.active {
            color: var(--primary-blue);
        }
        
        .tab-button.active:after {
            content: "";
            position: absolute;
            bottom: -1px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: var(--primary-blue);
        }
        
        .tab-content {
            display: none;
        }
        
        .tab-content.active {
            display: block;
        }
        
        /* ===== TABLES ===== */
        .table-container {
            overflow-x: auto;
            margin: 30px 0;
            border-radius: 8px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.05);
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
        }
        
        th, td {
            padding: 15px;
            text-align: left;
            border-bottom: 1px solid #e0e0e0;
        }
        
        th {
            background-color: var(--light-blue);
            color: var(--dark-blue);
            font-weight: 600;
        }
        
        tr:nth-child(even) {
            background-color: var(--gray);
        }
        
        tr:hover {
            background-color: #f0f7ff;
        }
        
        /* ===== PAYMENT SECTION ===== */
        .payment-section {
            background-color: var(--light-blue);
            padding: 50px 0;
            border-radius: 8px;
            margin: 40px 0;
        }
        
        .payment-options {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
            margin-top: 30px;
        }
        
        .payment-card {
            flex: 1 1 200px;
            background: var(--white);
            border-radius: 8px;
            padding: 25px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            max-width: 250px;
        }
        
        .payment-icon {
            font-size: 30px;
            margin-bottom: 15px;
            color: var(--primary-blue);
        }
        
        .payment-title {
            font-weight: 600;
            margin-bottom: 10px;
            color: var(--dark-blue);
        }
        
        /* ===== AUDIENCE SECTION ===== */
        .audience-section {
            margin: 60px 0;
        }
        
        .audience-cards {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 30px;
        }
        
        .audience-card {
            flex: 1 1 300px;
            background: var(--white);
            border-radius: 8px;
            padding: 25px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        
        .audience-card h3 {
            color: var(--primary-blue);
            margin-bottom: 15px;
            font-size: 20px;
        }
        
        .audience-list {
            list-style: none;
        }
        
        .audience-list li {
            margin-bottom: 10px;
            padding-left: 25px;
            position: relative;
        }
        
        .audience-list li:before {
            content: "→";
            color: var(--primary-blue);
            position: absolute;
            left: 0;
        }
        
        /* ===== BENEFITS SECTION ===== */
        .benefits-section {
            background-color: var(--light-blue);
            padding: 60px 0;
            margin: 40px 0;
        }
        
        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }
        
        .benefit-item {
            background: var(--white);
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        
        .benefit-title {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            font-weight: 600;
            color: var(--dark-blue);
        }
        
        .benefit-title:before {
            content: "✓";
            display: inline-block;
            width: 25px;
            height: 25px;
            background-color: var(--primary-blue);
            color: white;
            border-radius: 50%;
            text-align: center;
            line-height: 25px;
            margin-right: 10px;
            font-size: 14px;
        }
        
        /* ===== FINAL CTA ===== */
        .final-cta {
            text-align: center;
            padding: 80px 0;
            background: linear-gradient(135deg, var(--dark-blue) 0%, var(--primary-blue) 100%);
            color: white;
            margin-top: 60px;
        }
        
        .final-cta h2 {
            font-size: 36px;
            margin-bottom: 20px;
            color: white;
        }
        
        .final-cta p {
            font-size: 18px;
            max-width: 600px;
            margin: 0 auto 30px;
            opacity: 0.9;
        }
        
        .final-cta .button-group {
            margin-top: 30px;
        }
        
        .limited-badge {
            display: inline-block;
            background-color: #ff6b6b;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 600;
            margin-top: 20px;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        /* ===== FOOTER ===== */
        footer {
            background-color: var(--dark-blue);
            color: var(--white);
            padding: 40px 0;
            text-align: center;
        }
        
        footer p {
            margin-bottom: 10px;
            opacity: 0.8;
        }
        
        footer .logo {
            margin-bottom: 20px;
            display: inline-block;
            color: white;
        }
        
        /* ===== RESPONSIVE ===== */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 32px;
            }
            
            .hero p {
                font-size: 18px;
            }
            
            .button-group {
                flex-direction: column;
                align-items: center;
            }
            
            .button-primary, .button-secondary {
                width: 100%;
                max-width: 250px;
            }
            
            .programs {
                flex-direction: column;
                align-items: center;
            }
            
            .program-card {
                max-width: 100%;
            }
            
            .tabs {
                flex-wrap: wrap;
            }
            
            .tab-button {
                flex: 1 1 auto;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">AUTOMATE ACADEMY</div>
        </div>
    </header>
    
    <!-- HERO SECTION -->
    <section class="hero">
        <div class="container">
            <h1>Launch Your AI Automation Career — No Code. No Limits.</h1>
            <p>Master automation skills, build real systems, and start earning — even as a beginner.</p>
            <div class="button-group">
                <a href="#programs" class="button-primary">Explore Programs</a>
                <a href="https://forms.gle/R1PNwa2ZHtd7zgdBA" class="button-secondary">Enroll Now</a>
            </div>
        </div>
    </section>
    
    <!-- PROGRAM CARDS -->
    <section class="container" id="programs">
        <h2 class="section-title">Choose Your AI Automation Path</h2>
        
        <div class="programs">
            <div class="program-card">
                <h3>Automation Foundations Bootcamp</h3>
                <div class="program-meta">
                    <span class="program-price">$250</span>
                    <span class="program-duration">6 Weeks</span>
                </div>
                <p>Perfect for beginners to start automating immediately</p>
                
                <ul class="program-features">
                    <li>AI voice agents for calls & appointments</li>
                    <li>WhatsApp & website chatbots</li>
                    <li>Workflow automation</li>
                    <li>CRM integrations</li>
                </ul>
                
                <p class="program-audience">Best for: Beginners, freelancers, students</p>
                <a href="https://forms.gle/R1PNwa2ZHtd7zgdBA" class="program-button">Enroll Now</a>
            </div>
            
            <div class="program-card">
                <h3>AI Solutions Mastery Program</h3>
                <div class="program-meta">
                    <span class="program-price">$750</span>
                    <span class="program-duration">12 Weeks</span>
                </div>
                <p>Complete AI business blueprint for serious growth</p>
                
                #<ul class="program-features">
                    <li>Advanced AI tools & no-code apps</li>
                    <li>Content creation automation</li>
                    <li>AI marketing & sales systems</li>
                    <li>Enterprise-level projects</li>
                </ul>
                
                <p class="program-audience">Best for: Entrepreneurs, consultants</p>
                <a href="https://forms.gle/R1PNwa2ZHtd7zgdBA" class="program-button">Enroll Now</a>
            </div>
            
            <div class="program-card">
                <h3>Specialist Skill Courses</h3>
                <div class="program-meta">
                    <span class="program-price">From $80</span>
                    <span class="program-duration">2-4 Weeks</span>
                </div>
                <p>Focused learning on specific automation skills</p>
                
                <ul class="program-features">
                    <li>Voice AI specialist</li>
                    <li>Chatbot automation</li>
                    <li>Prompt engineering</li>
                    <li>AI app development</li>
                </ul>
                
                <p class="program-audience">Best for: Targeted skill development</p>
                <a href="#specialist-courses" class="program-button" onclick="openSpecialistTab()">Details Below ↓</a>
            </div>
        </div>
    </section>
    
    <!-- TABBED COURSE DETAILS -->
    <section class="container">
        <div class="tabs">
            <button class="tab-button active" onclick="openTab(event, 'specialist')">Specialist Courses</button>
            <button class="tab-button" onclick="openTab(event, 'bundles')">Program Bundles</button>
        </div>
        
        <div id="specialist" class="tab-content active">
            <div class="table-container">
                <table>
                    <thead>
                        <tr>
                            <th>Course Name</th>
                            <th>Duration</th>
                            <th>Price</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Voice AI Specialist</td>
                            <td>4 weeks</td>
                            <td>$120</td>
                        </tr>
                        <tr>
                            <td>Chatbot Automation</td>
                            <td>3 weeks</td>
                            <td>$100</td>
                        </tr>
                        <tr>
                            <td>Prompt Engineering</td>
                            <td>2 weeks</td>
                            <td>$80</td>
                        </tr>
                        <tr>
                            <td>AI App Development</td>
                            <td>3 weeks</td>
                            <td>$300</td>
                        </tr>
                        <tr>
                            <td>Content Creation AI</td>
                            <td>3 weeks</td>
                            <td>$250</td>
                        </tr>
                        <tr>
                            <td>CRM & Workflow Automation</td>
                            <td>4 weeks</td>
                            <td>$250</td>
                        </tr>
                        <tr>
                            <td>AI Sales & Marketing</td>
                            <td>3 weeks</td>
                            <td>$100</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
        
        <div id="bundles" class="tab-content">
            <div class="table-container">
                <table>
                    <thead>
                        <tr>
                            <th>Program</th>
                            <th>Price</th>
                            <th>Savings</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Foundations Bootcamp</td>
                            <td>$300</td>
                            <td>Save $150 vs separate courses</td>
                        </tr>
                        <tr>
                            <td>Mastery Program</td>
                            <td>$900</td>
                            <td>Save $540 vs separate courses</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </section>
    
    <!-- PAYMENT OPTIONS -->
   <!-- SPECIAL DISCOUNT SECTION -->
<section class="container discount-section">
    <h2 class="section-title">✨ Special Discount</h2>
    
    <div class="discount-card">
        <div class="discount-icon">👥</div>
        <div class="discount-content">
            <h3>Group/Team Enrollments</h3>
            <p>Get 10–25% off when you enroll with your team</p>
            <a href="https://wa.me/923197825613" class="discount-button">Inquire Now</a>
        </div>
    </div>
</section>
    
    <!-- AUDIENCE SECTION -->
 
    <!-- AUDIENCE SECTION -->
<section class="container audience-section">
    <h2 class="section-title">Who Is This For?</h2>
    
    <div class="audience-cards">
        <div class="audience-card">
            <h3>Choose Foundations if...</h3>
            <ul class="audience-list">
                <li>You're new to AI & automation</li>
                <li>Want fast, practical skills</li>
                <li>Starting part-time</li>
                <li>Budget-conscious</li>
            </ul>
        </div>
        
        <div class="audience-card">
            <h3>Choose Mastery if...</h3>
            <ul class="audience-list">
                <li>You want to launch a real AI business</li>
                <li>Need the full toolkit + strategy</li>
                <li>Want higher income & serious growth</li>
                <li>Ready to go all-in</li>
            </ul>
        </div>
        
        <div class="audience-card">
            <h3>Choose Specialist if...</h3>
            <ul class="audience-list">
                <li>You need one specific skill</li>
                <li>Already know some automation</li>
                <li>Want to explore before committing</li>
            </ul>
        </div>
    </div>
</section>
    
    <!-- BENEFITS SECTION -->
    <section class="benefits-section">
        <div class="container">
            <h2 class="section-title">What You Get</h2>
            
            <div class="benefits-grid">
                <div class="benefit-item">
                    <h3 class="benefit-title">Live Training</h3>
                    <p>Weekly interactive sessions with experts</p>
                </div>
                
                <div class="benefit-item">
                    <h3 class="benefit-title">Portfolio Projects</h3>
                    <p>Real-world automation systems for your portfolio</p>
                </div>
                
                <div class="benefit-item">
                    <h3 class="benefit-title">Certification</h3>
                    <p>Industry-recognized completion certificates</p>
                </div>
                
                <div class="benefit-item">
                    <h3 class="benefit-title">Private Community</h3>
                    <p>Access to exclusive network of automation professionals</p>
                </div>
                
                <div class="benefit-item">
                    <h3 class="benefit-title">Job Support</h3>
                    <p>Placement assistance and client referrals</p>
                </div>
                
                <div class="benefit-item">
                    <h3 class="benefit-title">Lifetime Access</h3>
                    <p>All course materials and future updates</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- FINAL CTA -->
    <section class="final-cta" id="enroll">
        <div class="container">
            <h2>Build. Automate. Grow.</h2>
            <p>Your AI automation career starts today. Choose your path and join our next cohort.</p>
            
            <div class="button-group">
                
                <a href="https://wa.me/923197825613" class="button-secondary">Talk to Us</a>
            </div>
            
            <div class="limited-badge">Limited slots available</div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <div class="logo">AUTOMATE ACADEMY</div>
            <p>The AI future belongs to builders. Don't get left behind.</p>
            <p>&copy; 2023 AUTOMATE ACADEMY. All rights reserved.</p>
        </div>
    </footer>
    
    <script>
        function openTab(evt, tabName) {
            // Hide all tab content
            var tabcontent = document.getElementsByClassName("tab-content");
            for (var i = 0; i < tabcontent.length; i++) {
                tabcontent[i].classList.remove("active");
            }
            
            // Remove active class from all tab buttons
            var tabbuttons = document.getElementsByClassName("tab-button");
            for (var i = 0; i < tabbuttons.length; i++) {
                tabbuttons[i].classList.remove("active");
            }
            
            // Show current tab and mark button as active
            document.getElementById(tabName).classList.add("active");
            evt.currentTarget.classList.add("active");
        }
    </script>
</body>
</html>

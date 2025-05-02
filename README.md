<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raghukul Chaudhary - Online Resume</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@700&family=Open+Sans:wght@400&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Open Sans', sans-serif;
        }
        body {
            line-height: 1.8;
            color: #333;
            background: #f5f5f5;
        }
        header {
            background: #2c3e50;
            color: white;
            padding: 1.5rem;
            text-align: center;
            border: none !important;
            box-shadow: none;
            line-height: 1;
        }
        header h1 {
            font-family: 'Roboto', sans-serif;
            font-size: 2.5rem;
            font-weight: 700;
            margin: 0;
            padding: 1rem 0;
            text-decoration: none !important;
            border: none !important;
            outline: none;
            box-shadow: none;
            background: transparent;
            display: block;
        }
        header h1::before, header h1::after {
            content: none !important;
        }
        nav {
            background: #f4f4f4;
            padding: 1rem;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 1rem;
        }
        nav li {
            flex: 1;
            max-width: 150px;
            text-align: center;
            padding: 0.5rem;
        }
        nav a {
            text-decoration: none;
            color: #008080;
            font-weight: 600;
            display: block;
        }
        nav a:hover {
            color: #00a3a3;
        }
        .section {
            padding: 2.5rem;
            max-width: 1000px;
            margin: 0 auto;
            background: #ffffff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .section-header {
            display: flex;
            align-items: center;
            margin-bottom: 1rem;
        }
        .section-header i {
            font-size: 20px;
            color: #004aad;
            margin-right: 8px;
            vertical-align: middle;
        }
        .section h3 {
            font-family: 'Roboto', sans-serif;
            font-size: 1.8rem;
            font-weight: 700;
            color: #004aad;
        }
        .section h4 {
            font-family: 'Roboto', sans-serif;
            font-size: 1.4rem;
            font-weight: 700;
            margin-bottom: 0.5rem;
        }
        .section p, .section ul {
            font-size: 1rem;
            margin-bottom: 1rem;
        }
        .section ul {
            list-style: disc;
            padding-left: 2rem;
        }
        #about p {
            text-align: justify;
        }
        .timeline {
            position: relative;
            padding-left: 3rem;
        }
        .timeline::before {
            content: '';
            position: absolute;
            left: 1rem;
            top: 0;
            bottom: 0;
            width: 4px;
            background: linear-gradient(to bottom, #854d0e, #d97706);
        }
        .experience-item {
            position: relative;
            margin-bottom: 2rem;
            padding: 1rem;
            background: linear-gradient(to right, #ffffff, #e6f0fa);
            border-radius: 6px;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .experience-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 8px rgba(0,0,0,0.15);
        }
        .experience-item::before {
            content: '\f058'; /* Checkmark icon */
            font-family: 'Font Awesome 5 Free';
            font-weight: 900;
            position: absolute;
            left: -2.25rem;
            top: 0.5rem;
            width: 24px;
            height: 24px;
            background: #854d0e;
            color: #fff;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            animation: pulse 2s infinite;
        }
        .date-badge {
            display: inline-block;
            background: #854d0e;
            color: #fff;
            padding: 0.2rem 0.5rem;
            border-radius: 4px;
            font-size: 0.9rem;
            margin-bottom: 0.5rem;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 0.5rem;
        }
        .contact-item i {
            font-size: 20px;
            color: #004aad;
            margin-right: 8px;
            vertical-align: middle;
        }
        .contact-item a, .contact-item span {
            color: #4B0082; /* Dark plum */
            text-decoration: confederation;
        }
        .contact-item a:hover {
            color: #007bff;
        }
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 1rem;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                gap: 0.5rem;
            }
            nav li {
                max-width: 100%;
                padding: 0.5rem;
            }
            header h1 {
                font-size: 1.8rem;
            }
            .section {
                padding: 1.5rem;
            }
            .timeline {
                padding-left: 2rem;
            }
            .timeline::before {
                left: 0.5rem;
                width: 3px;
            }
            .experience-item {
                padding: 0.75rem;
            }
            .experience-item::before {
                left: -1.75rem;
                width: 20px;
                height: 20px;
                font-size: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Quality Management System Expert in ISO:13485 (Medical Devices & IVD)</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#skills-expertise">Skills & Expertise</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about" class="section">
        <div class="section-header">
            <i class="fas fa-user"></i>
            <h3>About Me:</h3>
        </div>
        <p>4+ years of experience in Quality Management Systems (QMS) within the IVD-Medical Device industry. Proficient in key standards and regulations, including ISO 13485, ISO 14971, ISO 9001, and IMDR, with comprehensive expertise in the overall QMS process, Quality Assurance, and regulatory requirements for IVD licensing and documentation (Manufacturing License, Test License, MSC, and FSC). My skills include the preparation and implementation of process-related documentation, such as SOPs, CAPA, Non-Conformance reports, Process Validation, Internal Audits, Temperature Mapping and Monitoring (using tools like Themoclient, Temprecord, and Smartsensors), Change Control, DQ, IQ, OQ, PQ, Risk Analysis, Risk Management, and Training Management (ISO 10015).</p>
    </section>
    <section id="experience" class="section">
        <div class="section-header">
            <i class="fas fa-briefcase"></i>
            <h3>Experience:</h3>
        </div>
        <div class="timeline">
            <div class="experience-item">
                <div class="date-badge">Jul 2022 - Mar 2025</div>
                <h4>Quality Assurance Executive - Nulife</h4>
                <p>2 yrs 9 mos · Full-time</p>
                <p>Noida, Uttar Pradesh, India · On-site</p>
                <ul>
                    <li>Implemented and ensured compliance with the ISO 13485 standard.</li>
                    <li>Meticulously maintained complaint and nonconformance processing through records and tracking systems, including root cause analysis and corrective actions.</li>
                    <li>Documented quality assurance activities through internal reporting and audits.</li>
                    <li>Identified training needs and implemented actions to ensure company-wide compliance.</li>
                    <li>Ensured all devices were calibrated according to the established schedule.</li>
                    <li>Met customer expectations aligned with company objectives and monthly quality goals.</li>
                    <li>Communicated inspection results, proposed corrective actions, and wrote reports documenting product deficiencies and errors.</li>
                    <li>Conducted risk assessments and implemented mitigation strategies to ensure product safety and compliance with regulatory requirements.</li>
                    <li>Collaborated with cross-functional teams to integrate quality management processes into product development and manufacturing workflows.</li>
                    <li>Monitored and evaluated supplier performance to ensure raw materials and components meet quality specifications.</li>
                    <li>Developed and updated standard operating procedures (SOPs) to reflect best practices and maintained consistency in quality processes.</li>
                    <li>Analyzed quality data trends to identify opportunities for continuous improvement and process optimization.</li>
                    <li>Managed and documented change control processes to ensure all modifications to products, processes, or systems were evaluated, approved, and implemented in accordance with quality and regulatory standards.</li>
                    <li>Promptly reported problems or concerns to quality assurance head and senior management.</li>
                </ul>
            </div>
            <div class="experience-item">
                <div class="date-badge">Mar 2021 - Jul 2022</div>
                <h4>Quality Assurance Executive - Astam Diagno</h4>
                <p>1 yr 5 mos</p>
                <p>Rajasthan, India</p>
                <ul>
                    <li>Ensured effective implementation of SOPs and other applicable regulations across all areas.</li>
                    <li>Managed customer complaints, nonconforming cases, and change control, including evaluating the effectiveness of corrective and preventive actions (CAPA).</li>
                    <li>Ensured risk management is adequately implemented across all key processes.</li>
                    <li>Oversaw the validation, qualification, and calibration of equipment and instruments used for manufacturing, inspection, measuring, monitoring, and testing.</li>
                    <li>Prepared, compiled, and presented Management Review Meeting (MRM) data.</li>
                    <li>Prepared technical documents, such as Site Master Files (SMF) and Drug Master Files (DMF), for licensing purposes.</li>
                    <li>Ensured the effective implementation of the quality management system.</li>
                    <li>Assured quality at every stage of the manufacturing process.</li>
                    <li>Ensured compliance with national standards.</li>
                    <li>Oversaw customer feedback and post-market surveillance of IVD products.</li>
                    <li>Managed internal and external audits (surveillance).</li>
                    <li>Ensured training is conducted according to the established training plan.</li>
                </ul>
            </div>
        </div>
    </section>
    <section id="skills-expertise" class="section">
        <div class="section-header">
            <i class="fas fa-tools"></i>
            <h3>Skills & Expertise:</h3>
        </div>
        <ul>
            <li>Expert in ISO:13485, ISO:14971, ISO 9001 and overall IMDR compliance</li>
            <li>Quality Assurance and Regulatory Documentation</li>
            <li>Change Control Management, PDLM and Risk Analysis</li>
            <li>Product Hold, FCA and Recalls</li>
            <li>Initiate, Handle Non-Conformance and CAPA</li>
            <li>7-QC Tools & Root Cause Analysis (RCA)</li>
            <li>Complaint Handling Process</li>
            <li>Process Validation</li>
            <li>Internal Audits and Management Review</li>
            <li>Risk Management</li>
            <li>Temperature Mapping (Themoclient, Temprecord, Smartsensors)</li>
            <li>Training Management (ISO 10015)</li>
            <li>Handling Deviations (Planned and Unplanned)</li>
            <li>SAP ERP, TrackWise, QSEP, TcU</li>
        </ul>
    </section>
    <section id="contact" class="section">
        <div class="section-header">
            <i class="fas fa-address-card"></i>
            <h3>Contact:</h3>
        </div>
        <div class="contact-item">
            <i class="fas fa-envelope"></i>
            <a href="mailto:raghukulchaudhary@gmail.com">raghukulchaudhary@gmail.com</a>
        </div>
        <div class="contact-item">
            <i class="fas fa-phone"></i>
            <span>+91-7020067460</span>
        </div>
        <div class="contact-item">
            <i class="fab fa-linkedin"></i>
            <a href="https://in.linkedin.com/in/raghukulchaudhary" target="_blank">linkedin.com/in/raghukulchaudhary</a>
        </div>
    </section>
    <footer>
        <p>© 2025 Raghukul Chaudhary. All rights reserved.</p>
    </footer>
</body>
</html>

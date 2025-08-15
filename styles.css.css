:root {
            --primary: #1e3a8a;
            --primary-dark: #0d2a66;
            --secondary: #3b82f6;
            --accent: #f59e0b;
            --light: #f8fafc;
            --dark: #1e293b;
            --success: #10b981;
            --text: #334155;
            --text-light: #64748b;
            --shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            --transition: all 0.3s ease;
            --border-radius: 16px;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            color: var(--text);
            line-height: 1.6;
            background: linear-gradient(135deg, #f0f5ff 0%, #e6f0ff 100%);
            min-height: 100vh;
            position: relative;
            overflow-x: hidden;
        }

        body::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><rect width="100" height="100" fill="none" stroke="%231e3a8a" stroke-width="0.5" opacity="0.1"/></svg>');
            z-index: -1;
        }

        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            padding: 15px 0;
            box-shadow: var(--shadow);
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 15px;
            cursor: pointer;
        }

        .logo i {
            font-size: 28px;
            color: var(--accent);
        }

        .logo h1 {
            font-family: 'Roboto Slab', serif;
            font-weight: 600;
            font-size: 1.8rem;
        }

        /* Navigation */
        nav {
            display: flex;
            gap: 15px;
        }

        .nav-item {
            background: rgba(255, 255, 255, 0.1);
            padding: 8px 18px;
            border-radius: 50px;
            cursor: pointer;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 500;
        }

        .nav-item:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-2px);
        }

        .nav-item i {
            font-size: 1rem;
        }

        /* Page container */
        .page-container {
            display: none;
            padding: 40px 0;
        }

        .page-container.active {
            display: block;
        }

        /* Common styles for pages */
        .section-title {
            text-align: center;
            margin-bottom: 40px;
        }

        .section-title h2 {
            font-size: 2.2rem;
            color: var(--primary);
            position: relative;
            display: inline-block;
            padding-bottom: 15px;
        }

        .section-title h2::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: var(--accent);
            border-radius: 2px;
        }

        .section-title p {
            color: var(--text-light);
            margin-top: 10px;
            font-size: 1.1rem;
        }

        .content-card {
            background: white;
            border-radius: var(--border-radius);
            overflow: hidden;
            box-shadow: var(--shadow);
            margin-bottom: 30px;
            transition: var(--transition);
        }

        .content-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
        }

        .card-header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            padding: 20px;
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .card-header i {
            font-size: 1.5rem;
            color: var(--accent);
        }

        .card-body {
            padding: 25px;
        }

        /* Home Page Styles */
        .hero {
            background: linear-gradient(135deg, rgba(27, 58, 138, 0.9) 0%, rgba(15, 42, 102, 0.9) 100%);
            color: white;
            padding: 60px 30px;
            border-radius: var(--border-radius);
            margin-bottom: 40px;
            position: relative;
            overflow: hidden;
            text-align: center;
        }

        .hero::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="%23ffffff" fill-opacity="0.1" d="M0,160L48,165.3C96,171,192,181,288,186.7C384,192,480,192,576,170.7C672,149,768,107,864,112C960,117,1056,171,1152,192C1248,213,1344,203,1392,197.3L1440,192L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path></svg>');
            background-size: cover;
            background-position: bottom;
            z-index: 0;
        }

        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            margin: 0 auto;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
            opacity: 0.9;
        }

        .location-container {
            background: rgba(255, 255, 255, 0.15);
            border-radius: var(--border-radius);
            padding: 25px;
            backdrop-filter: blur(5px);
        }

        .location-container h3 {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            margin-bottom: 20px;
            font-weight: 500;
        }

        .location-input {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
        }

        .location-input input {
            flex: 1;
            padding: 14px 20px;
            border: none;
            border-radius: 50px;
            font-size: 1rem;
            background: rgba(255, 255, 255, 0.9);
        }

        .location-input button {
            background: var(--accent);
            color: white;
            border: none;
            padding: 0 30px;
            border-radius: 50px;
            font-weight: 600;
            font-size: 1rem;
            cursor: pointer;
            transition: var(--transition);
        }

        .location-input button:hover {
            background: #e69008;
            transform: translateY(-2px);
        }

        .or-divider {
            display: flex;
            align-items: center;
            margin: 20px 0;
        }

        .or-divider::before,
        .or-divider::after {
            content: "";
            flex: 1;
            height: 1px;
            background: rgba(255, 255, 255, 0.3);
        }

        .or-divider span {
            padding: 0 15px;
            color: rgba(255, 255, 255, 0.7);
        }

        .detect-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            width: 100%;
            padding: 14px;
            background: transparent;
            border: 2px solid rgba(255, 255, 255, 0.4);
            border-radius: 50px;
            color: white;
            font-weight: 500;
            font-size: 1rem;
            cursor: pointer;
            transition: var(--transition);
        }

        .detect-btn:hover {
            background: rgba(255, 255, 255, 0.1);
            border-color: rgba(255, 255, 255, 0.7);
        }

        /* Prayer Times Section */
        .current-location {
            background: white;
            padding: 15px 20px;
            border-radius: var(--border-radius);
            margin-bottom: 25px;
            display: flex;
            align-items: center;
            gap: 10px;
            box-shadow: var(--shadow);
            font-weight: 500;
        }

        .current-location i {
            color: var(--secondary);
        }

        /* Clock Section */
        .clock-section {
            background: white;
            border-radius: var(--border-radius);
            padding: 30px;
            margin-bottom: 40px;
            box-shadow: var(--shadow);
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
            text-align: center;
        }

        @media (min-width: 768px) {
            .clock-section {
                grid-template-columns: 1fr 1fr 1fr;
            }
        }

        .clock-section > div {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }

        .current-time {
            font-size: 2.8rem;
            font-weight: 700;
            color: var(--primary);
            font-family: 'Roboto Slab', serif;
        }

        .next-prayer-info {
            background: linear-gradient(135deg, var(--secondary) 0%, #2563eb 100%);
            padding: 20px;
            border-radius: var(--border-radius);
            color: white;
            width: 100%;
        }

        .next-prayer-info h3 {
            font-size: 1.8rem;
            margin-bottom: 10px;
        }

        .countdown {
            font-size: 2.8rem;
            font-weight: 700;
            color: var(--accent);
            font-family: 'Roboto Slab', serif;
        }

        .countdown-label {
            color: var(--text-light);
            font-size: 0.9rem;
            margin-top: 5px;
        }

        /* Prayer Grid */
        .prayer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .prayer-card {
            background: white;
            border-radius: var(--border-radius);
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: var(--transition);
        }

        .prayer-card.next-prayer {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            position: relative;
        }

        .prayer-card.next-prayer::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: var(--accent);
        }

        .prayer-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
        }

        .prayer-name {
            font-size: 1.4rem;
            font-weight: 600;
        }

        .prayer-time {
            font-size: 1.5rem;
            font-weight: 700;
            font-family: 'Roboto Slab', serif;
        }

        .prayer-body {
            padding: 20px;
        }

        .rakat-info {
            color: var(--text);
            margin-bottom: 10px;
            font-weight: 500;
        }

        .time-remaining {
            color: var(--text-light);
            font-size: 0.9rem;
        }

        /* Important Dates */
        .dates-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
        }

        .date-card {
            background: white;
            border-radius: var(--border-radius);
            overflow: hidden;
            box-shadow: var(--shadow);
        }

        .date-header {
            background: linear-gradient(135deg, var(--secondary) 0%, #2563eb 100%);
            color: white;
            padding: 20px;
            text-align: center;
        }

        .date-header .date-name {
            font-size: 1.5rem;
            font-weight: 600;
        }

        .date-body {
            padding: 25px;
        }

        .date-info {
            display: flex;
            margin-bottom: 15px;
            padding-bottom: 15px;
            border-bottom: 1px solid #eee;
        }

        .date-label {
            font-weight: 600;
            color: var(--primary);
            min-width: 60px;
        }

        .date-description {
            color: var(--text);
            line-height: 1.7;
        }

        /* Quran Video Grid */
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        
        .video-grid iframe {
            width: 100%;
            height: 200px;
            border-radius: var(--border-radius);
            border: none;
            box-shadow: var(--shadow);
        }

        /* Footer */
        footer {
            background: var(--dark);
            color: white;
            padding: 50px 0 20px;
        }

        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-bottom: 40px;
        }

        .footer-column h3 {
            margin-bottom: 20px;
            position: relative;
            padding-bottom: 10px;
        }

        .footer-column h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 3px;
            background: var(--accent);
        }

        .footer-column ul {
            list-style: none;
        }

        .footer-column ul li {
            margin-bottom: 12px;
        }

        .footer-column ul li a {
            color: #d1d5db;
            text-decoration: none;
            transition: var(--transition);
        }

        .footer-column ul li a:hover {
            color: var(--accent);
        }

        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #aaa;
            font-size: 0.9rem;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .header-container {
                flex-direction: column;
                gap: 15px;
            }
            
            nav {
                width: 100%;
                flex-wrap: wrap;
                justify-content: center;
            }
            
            .nav-item {
                font-size: 0.9rem;
                padding: 8px 15px;
            }
            
            .section-title h2 {
                font-size: 1.8rem;
            }
            
            .clock-section {
                grid-template-columns: 1fr;
                gap: 20px;
            }
            
            .current-time,
            .countdown {
                font-size: 2.2rem;
            }
        }
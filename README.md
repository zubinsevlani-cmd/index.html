<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zubin Sevlani | Web Developer</title>
    <style>
        /* Modern, Futuristic Aesthetic */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #0f172a 0%, #1e1b4b 100%);
            color: #f8fafc;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .profile-card {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 24px;
            padding: 40px;
            max-width: 450px;
            width: 100%;
            text-align: center;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }

        .profile-card:hover {
            transform: translateY(-5px);
        }

        /* Profile Image Setup */
        .avatar-container {
            position: relative;
            width: 150px;
            height: 150px;
            margin: 0 auto 24px;
        }

        .avatar {
            width: 100%;
            height: 100%;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #6366f1;
            box-shadow: 0 0 20px rgba(99, 102, 241, 0.5);
        }

        h1 {
            font-size: 2rem;
            font-weight: 700;
            margin-bottom: 8px;
            background: linear-gradient(to right, #38bdf8, #818cf8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .title {
            font-size: 1rem;
            color: #94a3b8;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 24px;
        }

        .bio {
            font-size: 0.95rem;
            color: #cbd5e1;
            line-height: 1.6;
            margin-bottom: 32px;
        }

        /* Contact Details Section */
        .contact-info {
            background: rgba(0, 0, 0, 0.2);
            border-radius: 12px;
            padding: 16px;
            margin-bottom: 24px;
            text-align: left;
        }

        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 12px;
            font-size: 0.9rem;
            color: #e2e8f0;
        }

        .contact-item:last-child {
            margin-bottom: 0;
        }

        .contact-item strong {
            color: #38bdf8;
            margin-right: 8px;
            width: 60px;
            display: inline-block;
        }

        .contact-item a {
            color: #fff;
            text-decoration: none;
            transition: color 0.2s ease;
        }

        .contact-item a:hover {
            color: #818cf8;
        }

        /* Call to Action Button */
        .btn {
            display: inline-block;
            background: linear-gradient(135deg, #4f46e5 0%, #06b6d4 100%);
            color: white;
            padding: 12px 32px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            letter-spacing: 0.5px;
            box-shadow: 0 4px 15px rgba(79, 70, 229, 0.4);
            transition: all 0.3s ease;
        }

        .btn:hover {
            box-shadow: 0 6px 20px rgba(79, 70, 229, 0.6);
            opacity: 0.95;
        }
    </style>
</head>
<body>

    <div class="profile-card">
        <div class="avatar-container">
            <!-- Save your AI enhanced photo as me.jpg in your GitHub project folder -->
            <img src="me.jpg" alt="Zubin Sevlani" class="avatar">
        </div>
        
        <h1>Zubin Sevlani</h1>
        <div class="title">Web Developer & Founder</div>
        
        <p class="bio">
            Hi, I'm Zubin! I am an ambitious entrepreneur building professional, creative, and high-performance websites for businesses absolutely free to grow my portfolio. Let's build your next digital vision together.
        </p>

        <div class="contact-info">
            <div class="contact-item">
                <strong>Email:</strong> 
                <a href="mailto:zubin.sevlani@gmail.com">zubin.sevlani@gmail.com</a>
            </div>
            <div class="contact-item">
                <strong>Phone:</strong> 
                <a href="tel:+9710567985067">+971 0567985067</a>
            </div>
        </div>

        <a href="mailto:zubin.sevlani@gmail.com" class="btn">Get A Free Website</a>
    </div>

</body>
</html>

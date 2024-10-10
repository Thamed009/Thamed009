<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thamed's Profile</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e0f7fa;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            animation: fadeIn 2s ease-in-out; /* Fade-in animation */
        }
        h1 {
            color: #00796b;
            text-align: center;
            font-size: 2.5em;
            animation: fadeIn 2s ease-in-out;
        }
        h2 {
            color: #004d40;
            border-bottom: 2px solid #004d40;
            padding-bottom: 10px;
            animation: slideIn 1.5s ease-out; /* Slide-in animation */
        }
        p {
            color: #555;
            font-size: 1.2em;
            line-height: 1.6;
        }
        .info, .location, .experience, .education, .skills, .qualities, .extra, .contact {
            margin-bottom: 30px;
        }
        .info {
            background-color: #b2dfdb;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1.5s ease-in-out;
        }
        /* Keyframes for fade-in animation */
        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }

        /* Keyframes for slide-in animation */
        @keyframes slideIn {
            0% {
                transform: translateX(-100%);
                opacity: 0;
            }
            100% {
                transform: translateX(0);
                opacity: 1;
            }
        }

        /* Hover animation for interaction */
        h1:hover {
            color: #004d40;
            transition: color 0.3s ease-in;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Welcome to Thamed's Profile</h1>

        <div class="info">
            <h2>Basic Information</h2>
            <p><strong>Name:</strong> Thamed</p>
            <p><strong>Age:</strong> 17</p>
            <p><strong>Date of Birth:</strong> 25/11/2008</p>
            <p><strong>Gender:</strong> Male</p>
            <p><strong>Nationality:</strong> Bangladeshi</p>
        </div>

        <div class="location">
            <h2>Location</h2>
            <p><strong>From:</strong> Dinajpur</p>
            <p><strong>Live in:</strong> Rosulpur Union Parishad</p>
        </div>

        <div class="family">
            <h2>Family Information</h2>
            <p><strong>Mother's Name:</strong> Parul Akter</p>
            <p><strong>Father's Name:</strong> Md Sakhawat Hossain</p>
        </div>

        <div class="experience">
            <h2>Work Experience</h2>
            <p>No professional work experience yet, but eager to learn and grow!</p>
        </div>

        <div class="education">
            <h2>Educational Background</h2>
            <p><strong>Studied at:</strong> Ramchandrapur Govt. Model Pilot High School, Dinajpur</p>
            <p><strong>SSC Grade:</strong> 4.31</p>
            <p><strong>Trade:</strong> 77 General Mechanic</p>
        </div>

        <div class="skills">
            <h2>Technical Skills</h2>
            <p><strong>Languages & Tools:</strong> HTML, JavaScript, CSS</p>
            <p><strong>Expertise:</strong> Extensive knowledge about computers, proficient in web development and troubleshooting technical issues.</p>
        </div>

        <div class="qualities">
            <h2>Personal Qualities</h2>
            <p><strong>Work Ethic:</strong> Hard worker, dedicated, and always eager to learn new things.</p>
            <p><strong>Loyalty:</strong> Loyal to the job and committed to delivering high-quality work.</p>
            <p><strong>Other Qualities:</strong> Self-motivated, detail-oriented, and able to work efficiently both individually and in teams.</p>
        </div>

        <div class="extra">
            <h2>Additional Information</h2>
            <p>Thamed is passionate about technology, especially in coding and web development. Currently exploring different tools and languages to build projects and gain hands-on experience.</p>
        </div>

        <div class="contact">
            <h2>Contact Information</h2>
            <p><strong>Phone:</strong> 01743194706</p>
            <p><strong>Email:</strong> rhamanthamed0@gmail.com</p>
        </div>
    </div>

</body>
</html>

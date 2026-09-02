
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calendar Reminders — Terms, Privacy & Sign Up</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            max-width: 640px;
            margin: 2rem auto;
            padding: 0 1.5rem;
            color: #333;
            line-height: 1.6;
        }
        h1 { font-size: 1.4rem; margin-bottom: 0.25rem; }
        h2 { font-size: 1.1rem; margin-top: 2rem; }
        p { margin: 0.75rem 0; }
        .updated { color: #888; font-size: 0.85rem; }
        .box {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1.25rem;
            margin: 1.5rem 0;
            background: #f9f9f9;
        }
        .box .field-label {
            display: block;
            font-size: 0.95rem;
            margin-bottom: 0.25rem;
            font-weight: 500;
        }
        .box input[type="text"],
        .box input[type="email"],
        .box input[type="tel"] {
            width: 100%;
            padding: 0.5rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 0.95rem;
            box-sizing: border-box;
        }
        .box button {
            margin-top: 0.5rem;
            padding: 0.5rem 1.25rem;
            background: #2563eb;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 0.95rem;
        }
        .box button:hover { background: #1d4ed8; }
        .sms-box {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1.25rem;
            margin: 1.5rem 0;
            background: #fff;
        }
        .sms-box h3 {
            font-size: 1rem;
            margin: 0 0 0.75rem 0;
        }
        .sms-box label {
            display: flex;
            align-items: flex-start;
            gap: 0.5rem;
            font-weight: normal;
            cursor: pointer;
            font-size: 0.95rem;
        }
        .sms-box input[type="checkbox"] { margin-top: 0.25rem; }
        .sms-box .disclosure {
            font-size: 0.82rem;
            color: #666;
            margin: 0.5rem 0 0 1.5rem;
        }
        .sms-box button {
            margin-top: 1rem;
            padding: 0.5rem 1.25rem;
            background: #16a34a;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 0.95rem;
        }
        .sms-box button:hover { background: #15803d; }
        .confirmation { display: none; color: #16a34a; margin-top: 0.75rem; font-weight: 500; }
    </style>
</head>
<body>
    <h1>Calendar Reminders</h1>
    <p class="updated">Last updated: September 2026</p>

    <h2>Create Your Account</h2>
    <div class="box">
        <span class="field-label">Name</span>
        <input type="text" id="name" placeholder="Your name">

        <span class="field-label">Email</span>
        <input type="email" id="email" placeholder="you@example.com">

        <button onclick="document.getElementById('signup-confirm').style.display='block'">Create account</button>
        <p class="confirmation" id="signup-confirm">&#10003; Account created. You can optionally add SMS reminders below.</p>
    </div>

    <h2>Optional: Add SMS Reminders</h2>
    <p>Already signed up? You can optionally receive text message reminders before your calendar events. This is completely separate from your account and not required to use Calendar Reminders.</p>
    <div class="sms-box">
        <h3>SMS Notifications (Optional)</h3>

        <span class="field-label">Phone number</span>
        <input type="tel" id="phone" placeholder="+1 (555) 123-4567">

        <label>
            <input type="checkbox" id="consent">
            <span>I agree to receive automated SMS calendar reminder notifications from Calendar Reminders at the phone number provided above. I understand I can reply STOP to opt out at any time.</span>
        </label>
        <p class="disclosure">Approx. 10-30 messages/month. Message and data rates may apply. This consent is entirely optional and is not required to use Calendar Reminders. No mobile information will be shared with third parties. Reply STOP to cancel. Reply HELP for assistance.</p>

        <button onclick="document.getElementById('sms-confirm').style.display='block'">Enable SMS reminders</button>
        <p class="confirmation" id="sms-confirm">&#10003; SMS reminders enabled. Reply STOP to any message to opt out.</p>
    </div>

    <h2>Terms of Service</h2>
    <p>Calendar Reminders is an automated notification service. It sends scheduled reminders before upcoming calendar events, plus a weekly schedule digest, to users via email or optionally via SMS through the Twilio messaging platform.</p>
    <p>No marketing, promotional, or third-party content is sent. Message frequency varies based on calendar activity, approximately 10-30 messages per month. Message and data rates may apply for SMS.</p>
    <p>SMS users may opt out at any time by replying STOP to any message. Reply HELP for support.</p>

    <h2>Privacy Policy</h2>
    <p>Calendar Reminders accesses Google Calendar data solely to determine upcoming event times and locations. Calendar data is read in real time and is not stored beyond the current execution.</p>
    <p>Phone numbers and message logs are used only for delivering notifications to users who have opted in to SMS. No personal data is sold, shared with, or disclosed to any third parties or affiliates for marketing or promotional purposes.</p>
    <p>No mobile opt-in data or information collected as part of this messaging program will be shared with third parties.</p>

    <h2>Contact</h2>
    <p>For questions, reply HELP to any message or contact the service operator directly.</p>
</body>
</html>

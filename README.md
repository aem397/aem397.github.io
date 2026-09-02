<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calendar Reminders — Terms, Privacy & SMS Opt-In</title>
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
        .opt-in-box {
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1.25rem;
            margin: 1.5rem 0;
            background: #f9f9f9;
        }
        .opt-in-box label {
            display: flex;
            align-items: flex-start;
            gap: 0.5rem;
            cursor: pointer;
            font-size: 0.95rem;
        }
        .opt-in-box input[type="checkbox"] { margin-top: 0.25rem; }
        .opt-in-box button {
            margin-top: 1rem;
            padding: 0.5rem 1.25rem;
            background: #2563eb;
            color: white;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 0.95rem;
        }
        .opt-in-box button:hover { background: #1d4ed8; }
        #confirmation { display: none; color: #16a34a; margin-top: 0.75rem; font-weight: 500; }
    </style>
</head>
<body>
    <h1>Calendar Reminders</h1>
    <p class="updated">Last updated: September 2026</p>

    <h2>SMS Opt-In</h2>
    <div class="opt-in-box">
        <p>By checking the box below, you consent to receive automated SMS notifications from Calendar Reminders, including event reminders and weekly schedule digests. Approximately 10–30 messages per month. Message and data rates may apply. Reply STOP at any time to cancel. Reply HELP for assistance. No mobile information will be shared with third parties.</p>
        <label>
            <input type="checkbox" id="consent">
            I agree to receive automated SMS calendar reminder notifications from Calendar Reminders. I understand I can reply STOP to opt out at any time.
        </label>
        <br>
        <button onclick="document.getElementById('confirmation').style.display='block'">Subscribe</button>
        <p id="confirmation">✓ You have opted in to Calendar Reminders.</p>
    </div>

    <h2>Terms of Service</h2>
    <p>Calendar Reminders is an automated SMS notification service. It sends scheduled text message reminders before upcoming calendar events, plus a weekly schedule digest, to subscribed users via the Twilio messaging platform.</p>
    <p>No marketing, promotional, or third-party content is sent. Message frequency varies based on calendar activity, approximately 10–30 messages per month. Message and data rates may apply.</p>
    <p>Users may opt out at any time by replying STOP to any message. Reply HELP for support.</p>

    <h2>Privacy Policy</h2>
    <p>Calendar Reminders accesses Google Calendar data solely to determine upcoming event times and locations. Calendar data is read in real time and is not stored beyond the current execution.</p>
    <p>Phone numbers and message logs are used only for delivering notifications to the subscribed user. No personal data is sold, shared with, or disclosed to any third parties or affiliates for marketing or promotional purposes.</p>
    <p>No mobile opt-in data or information collected as part of this messaging program will be shared with third parties.</p>

    <h2>Contact</h2>
    <p>For questions, reply HELP to any message or contact the service operator directly.</p>
</body>
</html>

CodeBidz (AuctionX) 🏆

Next-Generation Real-Time Auction & Bidding Ecosystem

Team Details

Team Name: EXCEPTION

Team Member: Vansh Gupta (Individual)

Unstop Profile: https://unstop.com/u/vanshgup41698

🚀 Overview

CodeBidz (AuctionX) is a high-performance, real-time auction platform designed to eliminate latency and ghost bids. It features a dual-dashboard system for Admins and Bidders, powered by a secure credit-locking mechanism and real-time database syncing.

💻 Tech Stack

Frontend: HTML5, CSS3, Vanilla Web Components

Styling: Custom CSS with Cyberpunk/Dark-Mode Aesthetics

Backend & Database: Firebase Firestore (Real-time NoSQL)

Authentication: Firebase Auth (JWT-based separate routing)

Hosting: Render / Firebase Hosting

(Note: While the initial pitch proposed MongoDB/Node.js/Socket.io, the architecture was pivoted to Firebase to achieve superior serverless sub-100ms real-time data sync without backend bottlenecking).

✨ Key Features

Real-Time Bidding: Sub-second bid updates broadcasted to all users simultaneously.

Credit Lock System: Bids temporarily lock credits. Outbid users receive instant automatic refunds.

Smart Proxy Auto-Bidding: Users set a max limit; the system automatically counter-bids on their behalf.

AI Bidding Assistant (Mocked for Demo): Suggests optimal bids, win probability, and urgency alerts.

Admin Analytics: Real-time Chart.js tracking of bidding velocity (Bids Per Minute).

Dual Portals: Completely separated secure authentication for Admins and Bidders.

🛠️ Setup Instructions

Because this project utilizes Firebase as a serverless backend, it requires zero local server configuration.

Clone or download the repository.

Open the project folder in VS Code.

Use the Live Server extension to launch index.html (or simply double-click index.html to open it in your browser).

Navigate to the Admin or Bidder portals via the homepage to interact with the platform.

⚠️ Limitations & Future Scope

Mocked AI: For the sake of the hackathon demo (to prevent CORS issues and protect API keys), the Anthropic Claude AI responses are simulated using intelligent client-side logic based on actual auction state (time left, bid count).

Payment Gateway: The credit system currently relies on Admin assignment. Real-world integration would require Stripe/Razorpay for purchasing credits.
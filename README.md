[![Typing SVG](https://readme-typing-svg.herokuapp.com?size=24&duration=3000&color=0E75B6&center=true&vCenter=true&width=700&lines=Software+Engineer;Building+AventoursNYC;Python+%7C+React+%7C+Node+%7C+MySQL;Full+Stack+Developer)](https://git.io/typing-svg)

## 🏗 Architecture Overview

User → React Frontend  
→ API Layer (Node / Python)  
→ Authentication Middleware  
→ Cloudflare Worker  
→ Private R2 Storage (Protected Audio Files)  
→ Stripe Payment Verification  

## 🎯 Why I Built This

Most audio tour platforms charge high commission fees and lack independent hosting options.  
I built AventoursNYC to create a scalable, low-overhead tourism platform with secure audio distribution and direct payment processing.

## 🔐 Security

- Audio files stored in private R2 bucket
- Access controlled via signed requests
- Stripe webhook verification implemented
- Server-side validation for all purchases
- No public file exposure

- ## 🛣 Roadmap

- [ ] Multi-language audio support
- [ ] Tour analytics dashboard
- [ ] AI voice narration generation
- [ ] Mobile PWA version
- [ ] Tour creator dashboard

## 🧠 Technical Challenges

- Preventing unauthorized audio downloads
- Handling Stripe webhook validation securely
- Designing scalable audio access control
- Managing environment variables across deployment
- 

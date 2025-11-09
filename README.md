# Watch & Earn Platform

A complete video watching and earning platform where users can watch videos and earn money. Built with Node.js/Express backend and React frontend.

## 🚀 Features

### Core Features
- **Video Watching & Earning**: Watch videos and earn rewards based on watch time
- **User Authentication**: Secure registration, login, and profile management
- **Reward System**: Track earnings, request withdrawals, and view statistics
- **Referral Program**: Earn bonuses by referring friends
- **Achievement System**: Unlock badges and milestones
- **Real-time Tracking**: Monitor watch progress and earnings

### User Features
- **Dashboard**: Overview of earnings, statistics, and recent activity
- **Video Library**: Browse videos by category, search, and filter
- **Watch History**: Track all watched videos and earnings
- **Withdrawal System**: Multiple payment methods (PayPal, Bank Transfer, Crypto)
- **Profile Management**: Update profile, change password, view achievements
- **Referral Dashboard**: Track referrals and referral earnings

### Admin Features
- **Video Management**: Upload, approve, and manage video content
- **User Management**: Monitor user activity and manage accounts
- **Analytics**: Track platform performance and user engagement
- **Withdrawal Processing**: Process and approve withdrawal requests

## 🛠 Tech Stack

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT (JSON Web Tokens)
- **Security**: bcryptjs, helmet, express-rate-limit
- **Email**: Nodemailer
- **Validation**: Built-in validation with error handling

### Frontend
- **Framework**: React 18
- **Routing**: React Router DOM
- **State Management**: React Query + Context API
- **Styling**: Tailwind CSS
- **UI Components**: Custom components with Framer Motion
- **HTTP Client**: Axios
- **Forms**: React Hook Form
- **Notifications**: React Hot Toast


## 🎯 Key Features Explained

### Video Watching & Earning
- Users watch videos and earn rewards based on watch time
- Minimum watch time requirements prevent abuse
- Rewards are calculated proportionally to watch duration
- Bonus rewards for completing videos

### Referral System
- Users get unique referral codes
- Referrer earns $1 for each successful referral
- Referred user gets $0.50 signup bonus
- Track referral statistics and earnings

### Withdrawal System
- Multiple payment methods (PayPal, Bank Transfer, Crypto)
- Minimum withdrawal amount of $5
- Processing times vary by method
- Withdrawal history tracking

### Achievement System
- Milestone-based achievements
- Video watching milestones
- Earning milestones
- Referral milestones
- Watch time milestones

## 🔒 Security Features

- **Password Hashing**: bcryptjs with salt rounds
- **JWT Authentication**: Secure token-based authentication
- **Rate Limiting**: Prevent abuse with express-rate-limit
- **Input Validation**: Request validation and sanitization
- **CORS Protection**: Configured for frontend communication
- **Helmet**: Security headers
- **Request Sanitization**: Prevent XSS and injection attacks

## 📱 Responsive Design

The frontend is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- All modern browsers


---

**Happy watching and earning! 🎬💰** 

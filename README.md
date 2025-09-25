<div align="center">

# Portfolio Full Stack

### Professional Full Stack Developer Portfolio

**Modern web application showcasing development skills with cutting-edge technologies**

![Next.js](https://img.shields.io/badge/Next.js-15.5.4-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript&logoColor=white)
![SASS](https://img.shields.io/badge/SASS-1.93.2-hotpink?style=for-the-badge&logo=sass&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-4.18-green?style=for-the-badge&logo=express&logoColor=white)

[🌟 Live Demo](#) · [📖 Documentation](#) · [🐛 Report Bug](#) · [✨ Request Feature](#)

</div>

---

## 🎯 **Overview**

This portfolio represents a **professional-grade full stack application** built with modern development practices. It demonstrates expertise in frontend development, backend architecture, database design, and DevOps workflows.

### ✨ **Key Highlights**
- 🏗️ **Monorepo Architecture** - Scalable workspace organization
- ⚡ **Next.js 15** with App Router for optimal performance
- 🎨 **SASS 7-1 Architecture** for maintainable styling
- 🔐 **Enterprise-grade Authentication** with NextAuth
- 📱 **Fully Responsive Design** - Mobile-first approach
- 🚀 **Production-ready** deployment configuration

---

## 🛠️ **Tech Stack**

<table>
<tr>
<td align="center"><strong>Frontend</strong></td>
<td align="center"><strong>Backend</strong></td>
<td align="center"><strong>Database</strong></td>
<td align="center"><strong>DevOps</strong></td>
</tr>
<tr>
<td>

- **Framework:** Next.js 15
- **Language:** TypeScript
- **Styling:** SASS (7-1 pattern)
- **State:** Zustand
- **Auth:** NextAuth.js
- **Icons:** Lucide React
- **Validation:** Zod

</td>
<td>

- **Runtime:** Node.js
- **Framework:** Express.js
- **Authentication:** JWT
- **Validation:** Joi/Zod
- **File Upload:** Multer
- **Email:** Nodemailer
- **Logging:** Winston

</td>
<td>

- **Database:** MongoDB
- **ODM:** Mongoose
- **Cloud Storage:** Cloudinary
- **Caching:** Redis
- **Search:** MongoDB Atlas

</td>
<td>

- **Version Control:** Git Flow
- **CI/CD:** GitHub Actions
- **Deployment:** Vercel/Railway
- **Monitoring:** Sentry
- **Analytics:** Vercel Analytics

</td>
</tr>
</table>

---

## 🚀 **Quick Start**

### **Prerequisites**
- Node.js 18.0.0 or higher
- npm 9.0.0 or higher
- MongoDB (local or Atlas)

### **Installation**
```bash
# Clone the repository
git clone https://github.com/Mordo253/portfolio-fullstack.git
cd portfolio-fullstack

# Install all dependencies (frontend + backend)
npm run install:all

# Set up environment variables
cp frontend/.env.example frontend/.env.local
cp backend/.env.example backend/.env

# Start development servers
npm run dev
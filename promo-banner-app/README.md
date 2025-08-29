# Promotional Banner Shopify App

This is a basic Shopify application built as part of a developer assignment.  
The app uses a **Theme App Extension** to inject a customizable promotional banner at the top of a Shopify store.

---

## 🚀 Core Functionality
- **Banner Injection**: Seamlessly adds a promotional banner to any Shopify theme that supports app blocks.  
- **Customization**: Store owners can customize the banner's text, background color, and text color directly from the Shopify Theme Editor.  
- **Easy Installation**: The app is installed as a block within the theme's header section, making it easy to add, reposition, or remove.  

---

## 🛠 Tech Stack
- **Backend**: Node.js with the Remix framework  
- **Frontend (Extension)**: Shopify Liquid  
- **Database ORM**: Prisma  
- **Deployment**: Vercel (backend) + Shopify (theme extension)  
- **Development Tools**: Shopify CLI  

---

## ⚙️ Local Development Setup

### Prerequisites
- A [Shopify Partner Account](https://partners.shopify.com/)  
- A development store with test data  
- Node.js (v18+) and npm installed  
- Shopify CLI installed  
  ```bash
  npm install -g @shopify/cli @shopify/theme

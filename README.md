# 🚀 Portfolio Admin Control Panel - Backend API# 🚀 Portfolio Admin Control Panel - Backend API# 🚀 Portfolio Admin Control Panel - Backend API

<p align="center"><p align="center"><!-- markdownlint-disable MD033 -->

<strong>Advanced Content Management System for Portfolio Administration</strong>

</p><strong>Advanced Content Management System for Portfolio Administration</strong><p align="center">

<p align="center">

<em>A comprehensive REST API built with Node.js, Express, and MongoDB</em></p> <strong>نظام إدارة محتوى متقدم للملفات الشخصية والحافظات الرقمية</strong>

</p>

<p align="center"></p>

---

<em>A comprehensive REST API built with Node.js, Express, and MongoDB</em><p align="center">

## 📋 Table of Contents

</p>  <strong>Advanced Content Management System for Portfolio Administration</strong>

- [Overview](#-overview)

- [Features](#-features)</p>

- [Prerequisites](#-prerequisites)

- [Installation](#-installation)---

- [Project Structure](#-project-structure)

- [Data Models](#-data-models)---

- [API Routes](#-api-routes)

- [Controllers](#-controllers)## 📋 Table of Contents

- [Authentication & Security](#-authentication--security)

- [File Upload](#-file-upload)## 📋 جدول المحتويات | Table of Contents

- [Usage Examples](#-usage-examples)

- [Troubleshooting](#-troubleshooting)- [Overview](#-overview)

- [Production Deployment](#-production-deployment)

- [License](#-license)- [Features](#-features)- [نظرة عامة](#-نظرة-عامة)

---- [Prerequisites](#-prerequisites)- [المميزات](#-المميزات)

## 🎯 Overview- [Installation](#-installation)- [المتطلبات](#-المتطلبات)

**Portfolio Admin Control Panel Backend** is a comprehensive REST API built with **Node.js**, **Express**, and **MongoDB**. It's designed to manage portfolio content, projects, services, and client information with professional-grade security and scalability.- [Project Structure](#-project-structure)- [التثبيت](#-التثبيت)

The system provides a complete suite of data management services including secure authentication, role-based access control, and file upload capabilities.- [Data Models](#-data-models)- [بنية المشروع](#-بنية-المشروع)

### Key Features:- [API Routes](#-api-routes)- [نماذج البيانات](#-نماذج-البيانات)

- ✅ **Secure Authentication** with JWT (JSON Web Tokens)

- ✅ **Password Encryption** using bcryptjs- [Controllers](#-controllers)- [المسارات والـ API](#-المسارات-والـ-api)

- ✅ **Role-Based Access Control** (Admin & Editor roles)

- ✅ **Optimized CORS** for frontend integration- [Authentication & Security](#-authentication--security)- [المتحكمات](#-المتحكمات)

- ✅ **Advanced Error Handling** with meaningful error messages

- ✅ **File Upload System** with file type and size validation- [File Upload](#-file-upload)- [المصادقة والأمان](#-المصادقة-والأمان)

---- [Usage Examples](#-usage-examples)- [رفع الملفات](#-رفع-الملفات)

## ✨ Features- [Troubleshooting](#-troubleshooting)- [أمثلة الاستخدام](#-أمثلة-الاستخدام)

### 🔐 Authentication & Authorization System- [Production Deployment](#-production-deployment)- [استكشاف الأخطاء](#-استكشاف-الأخطاء)

- User registration with data validation

- Secure login with JWT token generation- [License](#-license)- [الترخيص](#-الترخيص)

- Retrieve current user information

- Support for multiple roles (Admin, Editor)---

- Protected endpoints with middleware

## 🎯 Overview## 🎯 نظرة عامة

### 📊 Complete CRUD Operations

- **Home Section**: Manage hero title, description, images, and statistics**Portfolio Admin Control Panel Backend** is a comprehensive REST API built with **Node.js**, **Express**, and **MongoDB**. It's designed to manage portfolio content, projects, services, and client information with professional-grade security and scalability.**Portfolio Admin Control Panel Backend** هو نظام واجهة برمجية (API) متكامل مبني بـ **Node.js** و **Express** و **MongoDB**، مصمم لإدارة محتوى الملفات الشخصية والحافظات الرقمية بشكل احترافي.

- **About Section**: Company or individual information

- **Services**: Add, edit, and delete service offeringsThe system provides a complete suite of data management services including secure authentication, role-based access control, and file upload capabilities.يوفر النظام مجموعة شاملة من خدمات إدارة البيانات بما في ذلك المصادقة الآمنة والتحكم في الوصول ورفع الملفات.

- **Portfolio**: Manage projects and past work

- **Clients**: Client list with logo uploads and management### Key Features:### المميزات الرئيسية:

- **Contact Information**: Email, phone, address, and social media links

- **Navigation**: Manage navigation menus and links- ✅ **Secure Authentication** with JWT (JSON Web Tokens)

- **Footer**: Footer content and links management

- ✅ **Password Encryption** using bcryptjs- ✅ **مصادقة آمنة** باستخدام JWT

### 📤 File Upload System

- Secure image upload with format validation (JPEG, PNG, GIF, WebP)- ✅ **Role-Based Access Control** (Admin & Editor roles)- ✅ **تشفير كلمات المرور** بـ bcryptjs

- File size limit enforcement (5MB max)

- Automatic unique file naming to prevent conflicts- ✅ **Optimized CORS** for frontend integration- ✅ **إدارة أدوار المستخدمين** (Admin و Editor)

- HTTP serving of uploaded files

- ✅ **Advanced Error Handling** with meaningful error messages- ✅ **CORS محسّن** للتكامل مع الواجهات الأمامية

---

- ✅ **File Upload System** with file type and size validation- ✅ **معالجة الأخطاء** المتقدمة

## 🛠️ Prerequisites

- ✅ **رفع الملفات** مع التحقق من النوع والحجم

| Requirement | Minimum Version |

|------------|-----------------|---

| Node.js | v14.0.0 or higher |

| npm | v6.0.0 or higher |---

| MongoDB | v4.4.0 or higher |

## ✨ Features

### Required Tools:

- **MongoDB**: Local or cloud database (MongoDB Atlas recommended)## ✨ المميزات

- **Git**: Version control

- **Postman/Insomnia**: API testing (optional but recommended)### 🔐 Authentication & Authorization System

---- User registration with data validation### 🔐 نظام المصادقة والتفويض

## 📦 Installation- Secure login with JWT token generation

### Step 1: Clone the Repository- Retrieve current user information- تسجيل مستخدمين جدد بالتحقق من البيانات

```bash- Support for multiple roles (Admin, Editor)- تسجيل دخول آمن مع إصدار JWT

git clone https://github.com/your-username/portfolio-backend.git

cd portfolio-backend- Protected endpoints with middleware- استرجاع بيانات المستخدم الحالي

```

- دعم الأدوار المختلفة (Admin، Editor)

### Step 2: Install Dependencies

### 📊 Complete CRUD Operations

```bash

npm install- **Home Section**: Manage hero title, description, images, and statistics### 📊 عمليات CRUD المتكاملة

```

- **About Section**: Company or individual information

### Step 3: Configure Environment Variables

- **Services**: Add, edit, and delete service offerings- **الصفحة الرئيسية**: إدارة العنوان والوصف والصور والإحصائيات

Create a `.env` file in the root directory:

- **Portfolio**: Manage projects and past work- **حول**: معلومات عن الشركة أو الفرد

````env

# Database Configuration- **Clients**: Client list with logo uploads and management- **الخدمات**: إضافة وتعديل وحذف الخدمات المقدمة

MONGODB_URI=mongodb://localhost:27017/portfolio-admin

# Or use MongoDB Atlas- **Contact Information**: Email, phone, address, and social media links- **الحافظة**: إدارة المشاريع والأعمال السابقة

# MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/portfolio-admin

- **Navigation**: Manage navigation menus and links- **العملاء**: قائمة العملاء مع الشعارات (مع رفع الصور)

# Server Configuration

PORT=5000- **Footer**: Footer content and links management- **معلومات التواصل**: البريد الإلكتروني والهاتف والعنوان ووسائل التواصل الاجتماعي

NODE_ENV=development

- **التنقل**: إدارة قائمة التنقل والروابط

# Authentication

JWT_SECRET=your_super_secret_jwt_key_change_this_in_production_12345### 📤 File Upload System- **التذييل**: محتوى وروابط التذييل



# CORS Configuration- Secure image upload with format validation (JPEG, PNG, GIF, WebP)

CORS_ORIGIN=http://localhost:4200

```- File size limit enforcement (5MB max)### 📤 نظام رفع الملفات



### Step 4: Start the Server- Automatic unique file naming to prevent conflicts



#### Development Mode (with auto-reload):- HTTP serving of uploaded files- رفع آمن للصور مع التحقق من الصيغة (JPEG, PNG, GIF, WebP)

```bash

npm start- حد أقصى لحجم الملف (5MB)

````

---- تسميات فريدة تلقائية لتجنب التضارب

#### Production Mode:

`````bash- خدمة الملفات المرفوعة عبر HTTP

NODE_ENV=production npm start

```## 🛠️ Prerequisites



The server will run on `http://localhost:5000`---



---| Requirement | Minimum Version |



## 📂 Project Structure|------------|-----------------|## 🛠️ المتطلبات



```| Node.js | v14.0.0 or higher |

portfolio-backend/

├── config/| npm | v6.0.0 or higher || المتطلب | الإصدار الأدنى |

│   └── db.js                    # MongoDB connection settings

├── controllers/                 # Business logic| MongoDB | v4.4.0 or higher || ------- | --------------- |

│   ├── aboutController.js

│   ├── authController.js        # Authentication logic| Node.js | v14.0.0 أو أحدث |

│   ├── clientController.js

│   ├── contactController.js### Required Tools:| npm | v6.0.0 أو أحدث |

│   ├── footerController.js

│   ├── headerController.js- **MongoDB**: Local or cloud database (MongoDB Atlas recommended)| MongoDB | v4.4.0 أو أحدث |

│   ├── homeController.js

│   ├── navigationController.js- **Git**: Version control

│   ├── portfolioController.js

│   └── serviceController.js- **Postman/Insomnia**: API testing (optional but recommended)### الأدوات المطلوبة:

├── models/                      # MongoDB schemas

│   ├── User.js                  # User model with roles---- **MongoDB**: قاعدة بيانات (محلية أو سحابية مثل MongoDB Atlas)

│   ├── Home.js                  # Home section data

│   ├── About.js- **Git**: للتحكم بالإصدارات

│   ├── Service.js

│   ├── Portfolio.js## 📦 Installation- **Postman/Insomnia**: لاختبار API (اختياري)

│   ├── Client.js

│   ├── Contact.js### Step 1️⃣: Clone the Repository---

│   ├── Footer.js

│   ├── Header.js```bash## 📦 التثبيت

│   └── Navigation.js

├── routes/                      # API routesgit clone https://github.com/your-username/portfolio-backend.git

│   ├── auth.js                  # Authentication routes

│   ├── home.jscd portfolio-backend### الخطوة 1️⃣: استنساخ المستودع

│   ├── about.js

│   ├── services.js```

│   ├── portfolio.js

│   ├── clients.js````bash

│   ├── contact.js

│   ├── footer.js### Step 2️⃣: Install Dependenciesgit clone https://github.com/your-username/portfolio-backend.git

│   ├── header.js

│   └── navigation.jscd portfolio-backend

├── middleware/

│   └── auth.js                  # JWT verification middleware```bash```

├── uploads/

│   └── logos/                   # Uploaded files directorynpm install

├── scripts/

│   └── resetServices.js         # Database reset script```### الخطوة 2️⃣: تثبيت المكتبات

├── server.js                    # Main server file

├── package.json                 # Dependencies

├── nodemon.json                 # Nodemon configuration

└── README.md                    # Documentation### Step 3️⃣: Configure Environment Variables```bash

`````

npm install

---

Create a `.env` file in the root directory:```

## 📊 Data Models

### 👤 User Model

````env### الخطوة 3️⃣: إعداد متغيرات البيئة

```javascript

{# Database Configuration

  username: String (unique, required),

  email: String (unique, required, email format),MONGODB_URI=mongodb://localhost:27017/portfolio-adminأنشئ ملف `.env` في الجذر الرئيسي للمشروع:

  password: String (required, min length 6, hashed with bcrypt),

  role: String (enum: ['admin', 'editor'], default: 'editor'),# Or use MongoDB Atlas

  createdAt: Date,

  updatedAt: Date# MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/portfolio-admin```env

}

```# قاعدة البيانات



### 🏠 Home Model# Server ConfigurationMONGODB_URI=mongodb://localhost:27017/portfolio-admin



```javascriptPORT=5000# أو استخدم MongoDB Atlas

{

  heroTitle: String,NODE_ENV=development# MONGODB_URI=mongodb+srv://username:password@cluster.mongodb.net/portfolio-admin

  heroDescription: String,

  heroButtonText: String,

  heroButtonLink: String,

  ourWorkButtonText: String,# Authentication# إعدادات الخادم

  heroImage: String,

  stats: Array[JWT_SECRET=your_super_secret_jwt_key_change_this_in_production_12345PORT=5000

    {

      number: String,NODE_ENV=development

      label: String

    }# CORS Configuration

  ],

  createdAt: Date,CORS_ORIGIN=http://localhost:4200# المصادقة

  updatedAt: Date

}```JWT_SECRET=your_super_secret_jwt_key_change_this_in_production_12345

````

### 💼 Service Model

### Step 4️⃣: Start the Server# CORS

`````javascript

{CORS_ORIGIN=http://localhost:4200

  sectionTitle: String,

  sectionDescription: String,#### Development Mode (with auto-reload):```

  buttonText: String,

  services: Array[```bash

    {

      icon: String,npm start### الخطوة 4️⃣: تشغيل المشروع

      title: String,

      description: String````

    }

  ],#### للتطوير (مع المراقبة التلقائية):

  createdAt: Date,

  updatedAt: Date#### Production Mode:

}

````bash`bash



### 🎨 Portfolio ModelNODE_ENV=production npm startnpm start



```javascript````

{

  sectionTitle: String,

  sectionDescription: String,

  items: Array[The server will run on `http://localhost:5000`#### للإنتاج:

    {

      title: String,

      description: String,

      image: String,---```bash

      category: String,

      tags: Array[String],NODE_ENV=production npm start

      link: String,

      github: String,## 📂 Project Structure```

      createdAt: Date,

      updatedAt: Date

    }

  ]```---

}

```portfolio-backend/



### 👥 Client Model├── config/## 📂 بنية المشروع



```javascript│   └── db.js                    # MongoDB connection settings

{

  clientName: String,├── controllers/                 # Business logic```

  clientLogo: String,           // Image URL

  createdAt: Date,│   ├── aboutController.jsportfolio-backend/

  updatedAt: Date

}│   ├── authController.js        # Authentication logic├── config/

`````

│ ├── clientController.js│ └── db.js # إعدادات اتصال MongoDB

### 📞 Contact Model

│ ├── contactController.js├── controllers/ # منطق العمليات

````javascript

{│   ├── footerController.js│   ├── aboutController.js

  email: String,

  emails: Array[String],│   ├── headerController.js│   ├── authController.js        # مصادقة وتسجيل الدخول

  phone: String,

  phones: Array[String],│   ├── homeController.js│   ├── clientController.js

  sectionTitle: String,

  sectionDescription: String,│   ├── navigationController.js│   ├── contactController.js

  address: String,

  city: String,│   ├── portfolioController.js│   ├── footerController.js

  country: String,

  hours: String,│   └── serviceController.js│   ├── headerController.js

  socialLinks: Array[

    {├── models/                      # MongoDB schemas│   ├── homeController.js

      platform: String,

      url: String│   ├── User.js                  # User model with roles│   ├── navigationController.js

    }

  ],│   ├── Home.js                  # Home section data│   ├── portfolioController.js

  createdAt: Date,

  updatedAt: Date│   ├── About.js│   └── serviceController.js

}

```│   ├── Service.js├── models/                      # نماذج MongoDB



---│   ├── Portfolio.js│   ├── User.js                  # نموذج المستخدم



## 🔄 API Routes│   ├── Client.js│   ├── Home.js                  # نموذج الصفحة الرئيسية



### 🔐 Authentication Routes (`/api/auth`)│   ├── Contact.js│   ├── About.js



| Method | Endpoint | Description | Auth Required |│   ├── Footer.js│   ├── Service.js

|--------|----------|-------------|----------------|

| `POST` | `/auth/register` | Register a new user | ❌ |│   ├── Header.js│   ├── Portfolio.js

| `POST` | `/auth/login` | User login | ❌ |

| `GET` | `/auth/me` | Get current user info | ✅ |│   └── Navigation.js│   ├── Client.js



### 🏠 Home Routes (`/api/home`)├── routes/                      # API routes│   ├── Contact.js



| Method | Endpoint | Description | Auth Required |│   ├── auth.js                  # Authentication routes│   ├── Footer.js

|--------|----------|-------------|----------------|

| `GET` | `/home` | Get home section data | ❌ |│   ├── home.js│   ├── Header.js

| `PUT` | `/home/:id` | Update home section | ✅ |

│   ├── about.js│   ├── Navigation.js

### 🎨 Portfolio Routes (`/api/portfolio`)

│   ├── services.js│   └── User.js

| Method | Endpoint | Description | Auth Required |

|--------|----------|-------------|----------------|│   ├── portfolio.js├── routes/                      # مسارات API

| `GET` | `/portfolio` | Get all portfolio items | ❌ |

| `POST` | `/portfolio` | Add new portfolio item | ✅ |│   ├── clients.js│   ├── auth.js                  # المسارات المتعلقة بالمصادقة

| `PUT` | `/portfolio/:id` | Update portfolio item | ✅ |

| `DELETE` | `/portfolio/:id` | Delete portfolio item | ✅ |│   ├── contact.js│   ├── home.js



### 💼 Service Routes (`/api/services`)│   ├── footer.js│   ├── about.js



| Method | Endpoint | Description | Auth Required |│   ├── header.js│   ├── services.js

|--------|----------|-------------|----------------|

| `GET` | `/services` | Get all services | ❌ |│   └── navigation.js│   ├── portfolio.js

| `PUT` | `/services` | Update services | ✅ |

├── middleware/│   ├── clients.js

### 👥 Client Routes (`/api/clients`)

│   └── auth.js                  # JWT verification middleware│   ├── contact.js

| Method | Endpoint | Description | Auth Required |

|--------|----------|-------------|----------------|├── uploads/│   ├── footer.js

| `GET` | `/clients` | Get all clients | ❌ |

| `POST` | `/clients` | Add new client with logo | ✅ |│   └── logos/                   # Uploaded files directory│   ├── header.js

| `PUT` | `/clients/:id` | Update client | ✅ |

| `DELETE` | `/clients/:id` | Delete client | ✅ |├── scripts/│   └── navigation.js



### 📞 Contact Routes (`/api/contact`)│   └── resetServices.js         # Database reset script├── middleware/



| Method | Endpoint | Description | Auth Required |├── server.js                    # Main server file│   └── auth.js                  # التحقق من JWT

|--------|----------|-------------|----------------|

| `GET` | `/contact` | Get contact information | ❌ |├── package.json                 # Dependencies├── uploads/

| `PUT` | `/contact/:id` | Update contact info | ✅ |

├── nodemon.json                 # Nodemon configuration│   └── logos/                   # الملفات المرفوعة

### 📝 Additional Routes

└── README.md                    # Documentation├── scripts/

| Endpoint | Method | Description |

|----------|--------|-------------|```│   └── resetServices.js         # سكريبت لإعادة تعيين الخدمات

| `/api/health` | `GET` | Server health check |

| `/api/about` | `GET/PUT` | Manage about section |├── server.js                    # ملف الخادم الرئيسي

| `/api/header` | `GET/PUT` | Manage header |

| `/api/footer` | `GET/PUT` | Manage footer |---├── package.json                 # المكتبات والإعدادات

| `/api/navigation` | `GET/PUT` | Manage navigation |

├── nodemon.json                 # إعدادات nodemon

---

## 📊 Data Models└── README.md                    # التوثيق

## 👨‍💻 Controllers Overview

````

### authController.js

- **register()**: Create new user with password hashing### 👤 User Model

- **login()**: Verify credentials and generate JWT

- **getCurrentUser()**: Retrieve authenticated user data---

### homeController.js```javascript

- **getHome()**: Fetch home section data

- **updateHome()**: Update home section content{## 📊 نماذج البيانات

### portfolioController.js username: String (unique, required),

- **getPortfolio()**: Fetch all portfolio items

- **createPortfolioItem()**: Add new project email: String (unique, required, email format),### 👤 نموذج المستخدم (User Model)

- **updatePortfolioItem()**: Update project

- **deletePortfolioItem()**: Remove project password: String (required, min length 6, hashed with bcrypt),

### clientController.js role: String (enum: ['admin', 'editor'], default: 'editor'),```javascript

- **getClients()**: Fetch all clients

- **createClient()**: Add client with logo upload createdAt: Date,{

- **updateClient()**: Update client data

- **deleteClient()**: Remove client updatedAt: Date username: String (فريد، مطلوب),

### Other Controllers} email: String (فريد، مطلوب، صحة بريد إلكتروني),

Similar CRUD operations for services, contact, about, footer, header, and navigation

````password: String (مطلوب، طول أدنى 6 أحرف، مشفر),

---

  role: String (enum: ['admin', 'editor'], افتراضي: 'editor'),

## 🔐 Authentication & Security

### 🏠 Home Model  timestamps: true (تاريخ الإنشاء والتعديل)

### JWT Authentication Flow

}

1. **Registration**: User creates account

2. **Login**: User submits username and password```javascript```

3. **Token Generation**: Valid credentials generate JWT token

4. **Token Usage**: Send token in `Authorization` header{

5. **Verification**: Server validates token before processing request

  heroTitle: String,### 🏠 نموذج الصفحة الرئيسية (Home Model)

### Authorization Header Format:

```  heroDescription: String,

Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...

```  heroButtonText: String,```javascript



### Password Security:  heroButtonLink: String,{

- Passwords hashed with **bcryptjs** before storage

- Each password gets random salt  ourWorkButtonText: String,  heroTitle: String,          // عنوان البطل

- One-way encryption (unhashable)

- Salted hash prevents rainbow table attacks  heroImage: String,  heroDescription: String,    // وصف البطل



### Role-Based Access Control:  stats: Array[  heroButtonText: String,     // نص الزر

- **Admin**: Full access to all operations

- **Editor**: Limited editing permissions    {  heroButtonLink: String,     // رابط الزر



### Security Best Practices:      number: String,  ourWorkButtonText: String,  // نص زر الأعمال

- ✅ HTTPS in production

- ✅ Strong JWT_SECRET (change from default)      label: String  heroImage: String,          // صورة البطل

- ✅ Input validation on all routes

- ✅ CORS properly configured    }  stats: Array[               // الإحصائيات

- ✅ Rate limiting recommended

- ✅ Environment variables for secrets  ],    {



---  createdAt: Date,      number: String,         // الرقم



## 📤 File Upload System  updatedAt: Date      label: String          // الوصف



### Upload Configuration}    }



```javascript```  ],

const upload = multer({

  storage: storage,  timestamps: true

  limits: { fileSize: 5 * 1024 * 1024 }, // 5MB

  fileFilter: (req, file, cb) => {### 💼 Service Model}

    const allowedMimes = ['image/jpeg', 'image/png', 'image/gif', 'image/webp'];

    if (allowedMimes.includes(file.mimetype)) {```

      cb(null, true);

    } else {```javascript

      cb(new Error('Invalid file type'));

    }{### 💼 نموذج الخدمات (Service Model)

  },

});  sectionTitle: String,

````

sectionDescription: String,```javascript

### Supported Formats:

- ✅ JPEG (.jpg, .jpeg) buttonText: String,{

- ✅ PNG (.png)

- ✅ GIF (.gif) services: Array[ sectionTitle: String, // عنوان القسم

- ✅ WebP (.webp)

  { sectionDescription: String, // وصف القسم

### File Constraints:

- 📊 Maximum size: 5MB icon: String, buttonText: String, // نص الزر

- 🎨 Supported formats: JPEG, PNG, GIF, WebP

- 🔒 Uploaded to `/uploads/logos/` directory title: String, services: Array[ // قائمة الخدمات

### Upload Example: description: String {

```bash }      icon: String,                       // أيقونة (emoji أو رابط)

curl -X POST http://localhost:5000/api/clients \

  -H "Authorization: Bearer <token>" \  ],      title: String,                      // اسم الخدمة

  -F "clientName=Company Name" \

  -F "clientLogo=@path/to/image.png"  createdAt: Date,      description: String                 // وصف الخدمة

```

updatedAt: Date }

---

} ],

## 💡 Usage Examples

````timestamps: true

### 1️⃣ Register a New User

}

```bash

curl -X POST http://localhost:5000/api/auth/register \### 🎨 Portfolio Model```

  -H "Content-Type: application/json" \

  -d '{

    "username": "john_doe",

    "email": "john@example.com",```javascript### 🎨 نموذج الحافظة (Portfolio Model)

    "password": "password123",

    "role": "editor"{

  }'

```  sectionTitle: String,```javascript



**Response:**  sectionDescription: String,{

```json

{  items: Array[  sectionTitle: String,              // عنوان القسم

  "success": true,

  "message": "User registered successfully",    {  sectionDescription: String,        // وصف القسم

  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",

  "user": {      title: String,  items: Array[                      // المشاريع

    "id": "507f1f77bcf86cd799439011",

    "username": "john_doe",      description: String,    {

    "email": "john@example.com",

    "role": "editor"      image: String,      title: String,                // عنوان المشروع

  }

}      category: String,      description: String,          // الوصف

````

      tags: Array[String],      image: String,                // صورة المشروع

### 2️⃣ User Login

      link: String,      category: String,             // التصنيف

```````bash

curl -X POST http://localhost:5000/api/auth/login \      github: String,      tags: Array[String],          // الوسوم

  -H "Content-Type: application/json" \

  -d '{      createdAt: Date,      link: String,                 // رابط المشروع

    "username": "john_doe",

    "password": "password123"      updatedAt: Date      github: String                // رابط GitHub

  }'

```    }    }



### 3️⃣ Get Home Section  ]  ],



```bash}  timestamps: true

curl http://localhost:5000/api/home

``````}



**Response:**```

```json

{### 👥 Client Model

  "success": true,

  "data": {### 👥 نموذج العملاء (Client Model)

    "heroTitle": "Welcome to My Portfolio",

    "heroDescription": "I am a passionate developer",```javascript

    "stats": [

      { "number": "18+", "label": "Years Experience" },{```javascript

      { "number": "500+", "label": "Successful Projects" }

    ]  clientName: String,{

  }

}  clientLogo: String,           // Image URL  clientName: String,               // اسم العميل

```````

createdAt: Date, clientLogo: String, // شعار العميل (رابط الصورة)

### 4️⃣ Update Home Section (Requires Auth)

updatedAt: Date timestamps: true

`````bash

curl -X PUT http://localhost:5000/api/home/507f1f77bcf86cd799439011 \}}

  -H "Authorization: Bearer <token>" \

  -H "Content-Type: application/json" \````

  -d '{

    "heroTitle": "Welcome to My Updated Portfolio",### 📞 Contact Model### 📞 نموذج التواصل (Contact Model)

    "heroDescription": "I am a full-stack developer"

  }'`javascript`javascript

`````

{{

### 5️⃣ Get All Portfolio Items

email: String, email: String, // البريد الإلكتروني الرئيسي

```bash

curl http://localhost:5000/api/portfolioemails: Array[String], emails: Array[String], // قائمة البريد الإلكتروني الإضافية

```

phone: String, phone: String, // الهاتف الرئيسي

### 6️⃣ Add New Portfolio Item (Requires Auth)

phones: Array[String], phones: Array[String], // قائمة الهواتف الإضافية

````bash

curl -X POST http://localhost:5000/api/portfolio \sectionTitle: String, sectionTitle: String, // عنوان القسم

  -H "Authorization: Bearer <token>" \

  -H "Content-Type: application/json" \sectionDescription: String, sectionDescription: String, // وصف القسم

  -d '{

    "title": "E-Commerce Website",address: String, address: String, // العنوان

    "description": "Full-stack e-commerce platform",

    "image": "https://example.com/image.jpg",city: String, city: String, // المدينة

    "category": "Web Development",

    "tags": ["React", "Node.js", "MongoDB"],country: String, country: String, // الدولة

    "link": "https://example.com",

    "github": "https://github.com/example/repo"hours: String, hours: String, // ساعات العمل

  }'

```socialLinks: Array[ socialLinks: Array[ // روابط التواصل الاجتماعي



### 7️⃣ Get All Services    {    {



```bash      platform: String,      platform: String,             // (Facebook, Twitter, etc.)

curl http://localhost:5000/api/services

```      url: String      url: String



### 8️⃣ Upload Client Logo (Requires Auth)    }    }



```bash], ],

curl -X POST http://localhost:5000/api/clients \

  -H "Authorization: Bearer <token>" \createdAt: Date, timestamps: true

  -F "clientName=Tech Company Inc." \

  -F "clientLogo=@logo.png"updatedAt: Date}

````

}```

### 9️⃣ Get Contact Information

````

```bash

curl http://localhost:5000/api/contact---

```

---

### 🔟 Update Contact Information (Requires Auth)

## 🔄 المسارات والـ API

```bash

curl -X PUT http://localhost:5000/api/contact/507f1f77bcf86cd799439011 \## 🔄 API Routes

  -H "Authorization: Bearer <token>" \

  -H "Content-Type: application/json" \### 🔐 المسارات المتعلقة بالمصادقة (`/api/auth`)

  -d '{

    "email": "contact@example.com",### 🔐 Authentication Routes (`/api/auth`)

    "phone": "+1-555-123-4567",

    "address": "123 Main St, City, Country",| الطريقة | المسار           | الوصف                             | المصادقة |

    "city": "New York",

    "country": "United States"| Method | Endpoint | Description | Auth Required || ------- | ---------------- | --------------------------------- | -------- |

  }'

```|--------|----------|-------------|----------------|| `POST`  | `/auth/register` | تسجيل مستخدم جديد                 | ❌       |



---| `POST` | `/auth/register` | Register a new user | ❌ || `POST`  | `/auth/login`    | تسجيل دخول                        | ❌       |



## 🐛 Troubleshooting| `POST` | `/auth/login` | User login | ❌ || `GET`   | `/auth/me`       | الحصول على بيانات المستخدم الحالي | ✅       |



### Error: `ECONNREFUSED - Connection Refused`| `GET` | `/auth/me` | Get current user info | ✅ |

**Meaning**: Cannot connect to MongoDB

### 🏠 مسارات الصفحة الرئيسية (`/api/home`)

**Solution**:

```bash### 🏠 Home Routes (`/api/home`)

# Check if MongoDB is running

mongod| الطريقة | المسار      | الوصف                            | المصادقة |



# Verify MONGODB_URI in .env| Method | Endpoint | Description | Auth Required || ------- | ----------- | -------------------------------- | -------- |

# Default: mongodb://localhost:27017/portfolio-admin

```|--------|----------|-------------|----------------|| `GET`   | `/home`     | الحصول على محتوى الصفحة الرئيسية | ❌       |



### Error: `Port already in use`| `GET` | `/home` | Get home section data | ❌ || `PUT`   | `/home/:id` | تحديث الصفحة الرئيسية            | ✅       |

**Meaning**: Another process is using port 5000

| `PUT` | `/home/:id` | Update home section | ✅ |

**Solution**:

```bash### 🎨 مسارات الحافظة (`/api/portfolio`)

# Change port in .env

PORT=5001### 🎨 Portfolio Routes (`/api/portfolio`)



# Or find and kill the process using port 5000| الطريقة  | المسار           | الوصف                    | المصادقة |

# On Windows:

netstat -ano | findstr :5000| Method | Endpoint | Description | Auth Required || -------- | ---------------- | ------------------------ | -------- |

taskkill /PID <PID> /F

|--------|----------|-------------|----------------|| `GET`    | `/portfolio`     | الحصول على جميع المشاريع | ❌       |

# On Mac/Linux:

lsof -i :5000| `GET` | `/portfolio` | Get all portfolio items | ❌ || `POST`   | `/portfolio`     | إضافة مشروع جديد         | ✅       |

kill -9 <PID>

```| `POST` | `/portfolio` | Add new portfolio item | ✅ || `PUT`    | `/portfolio/:id` | تحديث مشروع              | ✅       |



### Error: `Invalid token`| `PUT` | `/portfolio/:id` | Update portfolio item | ✅ || `DELETE` | `/portfolio/:id` | حذف مشروع                | ✅       |

**Meaning**: JWT token is invalid, expired, or malformed

| `DELETE` | `/portfolio/:id` | Delete portfolio item | ✅ |

**Solution**:

- Login again to get a new token### 💼 مسارات الخدمات (`/api/services`)

- Ensure token is sent correctly in Authorization header

- Check that JWT_SECRET matches between server and token generation### 💼 Service Routes (`/api/services`)



### Error: `File too large`| الطريقة | المسار      | الوصف                   | المصادقة |

**Meaning**: Uploaded file exceeds 5MB limit

| Method | Endpoint | Description | Auth Required || ------- | ----------- | ----------------------- | -------- |

**Solution**:

- Compress images before upload|--------|----------|-------------|----------------|| `GET`   | `/services` | الحصول على جميع الخدمات | ❌       |

- Use smaller image sizes

- Check file dimensions and quality| `GET` | `/services` | Get all services | ❌ || `PUT`   | `/services` | تحديث الخدمات           | ✅       |



### Error: `CORS error`| `PUT` | `/services` | Update services | ✅ |

**Meaning**: Frontend domain is not allowed

### 👥 مسارات العملاء (`/api/clients`)

**Solution**:

```env### 👥 Client Routes (`/api/clients`)

# Update CORS_ORIGIN in .env

CORS_ORIGIN=http://localhost:4200| الطريقة  | المسار         | الوصف                       | المصادقة |

# Or use the exact frontend URL in production

```| Method | Endpoint | Description | Auth Required || -------- | -------------- | --------------------------- | -------- |



---|--------|----------|-------------|----------------|| `GET`    | `/clients`     | الحصول على جميع العملاء     | ❌       |



## 🔧 Important Environment Variables| `GET` | `/clients` | Get all clients | ❌ || `POST`   | `/clients`     | إضافة عميل جديد (برفع شعار) | ✅       |



| Variable | Default | Description || `POST` | `/clients` | Add new client with logo | ✅ || `PUT`    | `/clients/:id` | تحديث عميل                  | ✅       |

|----------|---------|-------------|

| `MONGODB_URI` | `mongodb://localhost:27017/portfolio-admin` | Database connection string || `PUT` | `/clients/:id` | Update client | ✅ || `DELETE` | `/clients/:id` | حذف عميل                    | ✅       |

| `PORT` | `5000` | Server port |

| `JWT_SECRET` | - | Secret key for JWT signing (CRITICAL) || `DELETE` | `/clients/:id` | Delete client | ✅ |

| `NODE_ENV` | `development` | Environment (development/production) |

| `CORS_ORIGIN` | `http://localhost:4200` | Allowed frontend URL |### 📞 مسارات التواصل (`/api/contact`)



---### 📞 Contact Routes (`/api/contact`)



## 📋 Dependencies| الطريقة | المسار         | الوصف                      | المصادقة |



| Package | Version | Purpose || Method | Endpoint | Description | Auth Required || ------- | -------------- | -------------------------- | -------- |

|---------|---------|---------|

| **express** | ^4.18.2 | Web framework ||--------|----------|-------------|----------------|| `GET`   | `/contact`     | الحصول على معلومات التواصل | ❌       |

| **mongoose** | ^7.5.0 | MongoDB ODM |

| **bcryptjs** | ^2.4.3 | Password hashing || `GET` | `/contact` | Get contact information | ❌ || `PUT`   | `/contact/:id` | تحديث معلومات التواصل      | ✅       |

| **jsonwebtoken** | ^9.0.2 | JWT creation/verification |

| **dotenv** | ^16.3.1 | Environment variable management || `PUT` | `/contact/:id` | Update contact info | ✅ |

| **cors** | ^2.8.5 | CORS middleware |

| **express-validator** | ^7.0.0 | Input validation |### 📝 المسارات الإضافية

| **multer** | ^1.4.5-lts.1 | File upload handling |

| **nodemon** | ^3.0.1 | Development auto-reload |### 📝 Additional Routes



---| المسار            | الطريقة   | الوصف                 |



## 🚀 Production Deployment Checklist| Endpoint | Method | Description || ----------------- | --------- | --------------------- |



Before deploying to production:|----------|--------|-------------|| `/api/health`     | `GET`     | التحقق من حالة الخادم |



- [ ] Change `JWT_SECRET` to a strong random value| `/api/health` | `GET` | Server health check || `/api/about`      | `GET/PUT` | إدارة قسم حول         |

  ```bash

  node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"| `/api/about` | `GET/PUT` | Manage about section || `/api/header`     | `GET/PUT` | إدارة الرأس           |

  ```

- [ ] Use MongoDB Atlas or managed MongoDB service| `/api/header` | `GET/PUT` | Manage header || `/api/footer`     | `GET/PUT` | إدارة التذييل         |

- [ ] Enable HTTPS/SSL certificate

- [ ] Set `CORS_ORIGIN` to production domain| `/api/footer` | `GET/PUT` | Manage footer || `/api/navigation` | `GET/PUT` | إدارة التنقل          |

- [ ] Set `NODE_ENV=production`

- [ ] Add rate limiting middleware| `/api/navigation` | `GET/PUT` | Manage navigation |

- [ ] Enable request logging

- [ ] Use process manager (PM2)---

- [ ] Set up monitoring and alerting

- [ ] Regular database backups---

- [ ] Keep dependencies updated

## 👨‍💻 المتحكمات (Controllers)

### Deployment with PM2:

## 👨‍💻 Controllers Overview

```bash

npm install -g pm2كل متحكم يحتوي على دوال للتعامل مع عمليات معينة:



# Start with PM2### authController.js

pm2 start server.js --name "portfolio-api"

- **register()**: Create new user with password hashing### authController.js

# Save PM2 configuration

pm2 save- **login()**: Verify credentials and generate JWT



# Enable PM2 startup- **getCurrentUser()**: Retrieve authenticated user data- **register()**: تسجيل مستخدم جديد مع تشفير كلمة المرور

pm2 startup

```- **login()**: التحقق من بيانات المستخدم وإصدار JWT



---### homeController.js- **getCurrentUser()**: استرجاع بيانات المستخدم الحالي (يتطلب JWT)



## 🔒 Security Best Practices- **getHome()**: Fetch home section data



1. **Keep Dependencies Updated**- **updateHome()**: Update home section content### homeController.js

   ```bash

   npm audit

   npm audit fix

   ```### portfolioController.js- **getHome()**: استرجاع بيانات الصفحة الرئيسية



2. **Never Commit `.env` File**- **getPortfolio()**: Fetch all portfolio items- **updateHome()**: تحديث محتوى الصفحة الرئيسية

   ```bash

   echo ".env" >> .gitignore- **createPortfolioItem()**: Add new project

   ```

- **updatePortfolioItem()**: Update project### portfolioController.js

3. **Use HTTPS in Production**

   - Obtain SSL certificate- **deletePortfolioItem()**: Remove project

   - Redirect HTTP to HTTPS

- **getPortfolio()**: استرجاع جميع المشاريع

4. **Input Validation**

   - All endpoints validate input### clientController.js- **createPortfolioItem()**: إضافة مشروع جديد

   - Use express-validator

- **getClients()**: Fetch all clients- **updatePortfolioItem()**: تعديل مشروع

5. **Rate Limiting**

   - Implement for authentication endpoints- **createClient()**: Add client with logo upload- **deletePortfolioItem()**: حذف مشروع

   - Prevent brute force attacks

- **updateClient()**: Update client data

6. **CORS Configuration**

   - Specify exact origins- **deleteClient()**: Remove client### clientController.js

   - Limit methods and headers



7. **Database Security**

   - Use strong passwords### Other Controllers- **getClients()**: استرجاع جميع العملاء

   - Enable authentication

   - Regular backupsSimilar CRUD operations for services, contact, about, footer, header, and navigation- **createClient()**: إضافة عميل جديد مع رفع الشعار



---- **updateClient()**: تعديل بيانات العميل



## 📚 Additional Resources---- **deleteClient()**: حذف عميل



- [Express.js Documentation](https://expressjs.com/)

- [MongoDB Documentation](https://docs.mongodb.com/)

- [Mongoose Documentation](https://mongoosejs.com/)## 🔐 Authentication & Security### وغيرها من المتحكمات الأخرى...

- [JWT Introduction](https://jwt.io/)

- [bcryptjs GitHub](https://github.com/dcodeIO/bcrypt.js)

- [Node.js Best Practices](https://nodejs.org/en/docs/guides/)

### JWT Authentication Flow---

---



## 🤝 Contributing

1. **Registration**: User creates account## 🔐 المصادقة والأمان

Contributions are welcome! Please follow these steps:

2. **Login**: User submits username and password

1. Fork the repository

2. Create a feature branch (`git checkout -b feature/AmazingFeature`)3. **Token Generation**: Valid credentials generate JWT token### آلية المصادقة (JWT - JSON Web Token)

3. Commit changes (`git commit -m 'Add AmazingFeature'`)

4. Push to branch (`git push origin feature/AmazingFeature`)4. **Token Usage**: Send token in `Authorization` header

5. Open a Pull Request

5. **Verification**: Server validates token before processing request1. **التسجيل**: المستخدم ينشئ حسابًا جديدًا

---

2. **تسجيل الدخول**: المستخدم يدخل اسم المستخدم وكلمة المرور

## 📧 Support

### Authorization Header Format:3. **إصدار التوكن**: إذا كانت البيانات صحيحة، يتم إصدار JWT

For issues, questions, or suggestions:

```4. **الاستخدام**: يتم إرسال التوكن في رأس الطلب (`Authorization: Bearer <token>`)

- 📧 Email: support@example.com

- 🐛 Report Issues: [GitHub Issues](https://github.com/your-username/portfolio-backend/issues)Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...5. **التحقق**: الخادم يتحقق من صحة التوكن قبل تنفيذ العملية

- 💬 Discussions: [GitHub Discussions](https://github.com/your-username/portfolio-backend/discussions)

````

---

### مثال على الرأس:

## 📜 License

### Password Security:

This project is licensed under the ISC License - see the LICENSE file for details.

- Passwords hashed with **bcryptjs** before storage```

````

ISC License- Each password gets random saltAuthorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...



Copyright (c) 2024- One-way encryption (unhashable)```



Permission to use, copy, modify, and/or distribute this software for any- Salted hash prevents rainbow table attacks

purpose with or without fee is hereby granted, provided that the above

copyright notice and this permission notice appear in all copies.### تشفير كلمات المرور:

````

### Role-Based Access Control:

---

- **Admin**: Full access to all operations- يتم استخدام **bcryptjs** لتشفير كلمات المرور

<p align="center">

<strong>Built with ❤️ for Portfolio Management</strong><br>- **Editor**: Limited editing permissions- كل كلمة مرور تحصل على salt عشوائي

<em>Portfolio Admin Control Panel Backend v1.0.0</em>

</p>- الكلمات المرور المشفرة لا يمكن فكها

### Security Best Practices:

- ✅ HTTPS in production### الأدوار والصلاحيات:

- ✅ Strong JWT_SECRET (change from default)

- ✅ Input validation on all routes- **Admin**: الوصول الكامل لجميع العمليات

- ✅ CORS properly configured- **Editor**: محرر مقيد

- ✅ Rate limiting recommended

- ✅ Environment variables for secrets---

---## 📤 رفع الملفات

## 📤 File Upload System### إعدادات رفع الملفات:

### Upload Configuration```javascript

const upload = multer({

````javascript storage: storage,

const upload = multer({  limits: { fileSize: 5 * 1024 * 1024 }, // 5MB

  storage: storage,  fileFilter: (req, file, cb) => {

  limits: { fileSize: 5 * 1024 * 1024 }, // 5MB    const allowedMimes = ["image/jpeg", "image/png", "image/gif", "image/webp"];

  fileFilter: (req, file, cb) => {    if (allowedMimes.includes(file.mimetype)) {

    const allowedMimes = ['image/jpeg', 'image/png', 'image/gif', 'image/webp'];      cb(null, true);

    if (allowedMimes.includes(file.mimetype)) {    } else {

      cb(null, true);      cb(new Error("صيغة ملف غير صحيحة"));

    } else {    }

      cb(new Error('Invalid file type'));  },

    }});

  },```

});

```### الصيغ المدعومة:



### Supported Formats:- ✅ JPEG (.jpg, .jpeg)

- ✅ JPEG (.jpg, .jpeg)- ✅ PNG (.png)

- ✅ PNG (.png)- ✅ GIF (.gif)

- ✅ GIF (.gif)- ✅ WebP (.webp)

- ✅ WebP (.webp)

### الحد الأقصى للحجم:

### File Constraints:

- 📊 Maximum size: 5MB- 📊 5 ميجابايت (5MB)

- 🎨 Supported formats: JPEG, PNG, GIF, WebP

- 🔒 Uploaded to `/uploads/logos/` directory### مثال على رفع صورة:



### Upload Example:```bash

curl -X POST http://localhost:5000/api/clients \

```bash  -H "Authorization: Bearer <token>" \

curl -X POST http://localhost:5000/api/clients \  -F "clientName=Company Name" \

  -H "Authorization: Bearer <token>" \  -F "clientLogo=@path/to/image.png"

  -F "clientName=Company Name" \```

  -F "clientLogo=@path/to/image.png"

```---



---## 💡 أمثلة الاستخدام



## 💡 Usage Examples### 1️⃣ تسجيل مستخدم جديد



### 1️⃣ Register a New User```bash

curl -X POST http://localhost:5000/api/auth/register \

```bash  -H "Content-Type: application/json" \

curl -X POST http://localhost:5000/api/auth/register \  -d '{

  -H "Content-Type: application/json" \    "username": "john_doe",

  -d '{    "email": "john@example.com",

    "username": "john_doe",    "password": "password123",

    "email": "john@example.com",    "role": "editor"

    "password": "password123",  }'

    "role": "editor"```

  }'

```**الرد:**



**Response:**```json

```json{

{  "success": true,

  "success": true,  "message": "تم التسجيل بنجاح",

  "message": "User registered successfully",  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9..."

  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",}

  "user": {```

    "id": "507f1f77bcf86cd799439011",

    "username": "john_doe",### 2️⃣ تسجيل الدخول

    "email": "john@example.com",

    "role": "editor"```bash

  }curl -X POST http://localhost:5000/api/auth/login \

}  -H "Content-Type: application/json" \

```  -d '{

    "username": "john_doe",

### 2️⃣ User Login    "password": "password123"

  }'

```bash```

curl -X POST http://localhost:5000/api/auth/login \

  -H "Content-Type: application/json" \### 3️⃣ الحصول على الصفحة الرئيسية

  -d '{

    "username": "john_doe",```bash

    "password": "password123"curl http://localhost:5000/api/home

  }'```

````

### 4️⃣ تحديث الصفحة الرئيسية (يتطلب التحقق)

### 3️⃣ Get Home Section

````bash

```bashcurl -X PUT http://localhost:5000/api/home/1 \

curl http://localhost:5000/api/home  -H "Authorization: Bearer <token>" \

```  -H "Content-Type: application/json" \

  -d '{

**Response:**    "heroTitle": "Welcome to My Portfolio",

```json    "heroDescription": "I am a passionate developer"

{  }'

  "success": true,```

  "data": {

    "heroTitle": "Welcome to My Portfolio",### 5️⃣ إضافة خدمة جديدة

    "heroDescription": "I am a passionate developer",

    "stats": [```bash

      { "number": "18+", "label": "Years Experience" },curl -X POST http://localhost:5000/api/services \

      { "number": "500+", "label": "Successful Projects" }  -H "Authorization: Bearer <token>" \

    ]  -H "Content-Type: application/json" \

  }  -d '{

}    "icon": "💻",

```    "title": "Web Development",

    "description": "Professional web development services"

### 4️⃣ Update Home Section (Requires Auth)  }'

````

````bash

curl -X PUT http://localhost:5000/api/home/507f1f77bcf86cd799439011 \### 6️⃣ رفع شعار عميل جديد

  -H "Authorization: Bearer <token>" \

  -H "Content-Type: application/json" \```bash

  -d '{curl -X POST http://localhost:5000/api/clients \

    "heroTitle": "Welcome to My Updated Portfolio",  -H "Authorization: Bearer <token>" \

    "heroDescription": "I am a full-stack developer"  -F "clientName=Awesome Company" \

  }'  -F "clientLogo=@logo.png"

````

### 5️⃣ Get All Portfolio Items---

````bash## 🐛 استكشاف الأخطاء

curl http://localhost:5000/api/portfolio

```### الخطأ: `ECONNREFUSED`



### 6️⃣ Add New Portfolio Item (Requires Auth)**المعنى**: فشل الاتصال بـ MongoDB



```bash**الحل**:

curl -X POST http://localhost:5000/api/portfolio \

  -H "Authorization: Bearer <token>" \```bash

  -H "Content-Type: application/json" \# تأكد من تشغيل MongoDB

  -d '{mongod

    "title": "E-Commerce Website",

    "description": "Full-stack e-commerce platform",# أو تحقق من MONGODB_URI في .env

    "image": "https://example.com/image.jpg",```

    "category": "Web Development",

    "tags": ["React", "Node.js", "MongoDB"],### الخطأ: `Port already in use`

    "link": "https://example.com",

    "github": "https://github.com/example/repo"**المعنى**: المنفذ مستخدم من قبل تطبيق آخر

  }'

```**الحل**:



### 7️⃣ Get All Services```bash

# غير المنفذ في .env

```bashPORT=5001

curl http://localhost:5000/api/services

```# أو اقتل العملية المستخدمة للمنفذ

# على Windows:

### 8️⃣ Upload Client Logo (Requires Auth)netstat -ano | findstr :5000

taskkill /PID <PID> /F

```bash```

curl -X POST http://localhost:5000/api/clients \

  -H "Authorization: Bearer <token>" \### الخطأ: `Invalid token`

  -F "clientName=Tech Company Inc." \

  -F "clientLogo=@logo.png"**المعنى**: التوكن منتهي الصلاحية أو غير صحيح

````

**الحل**:

### 9️⃣ Get Contact Information

- سجل الدخول مرة أخرى للحصول على توكن جديد

````bash- تأكد من إرسال التوكن بشكل صحيح في الرأس

curl http://localhost:5000/api/contact

```### الخطأ: `File too large`



### 🔟 Update Contact Information (Requires Auth)**المعنى**: حجم الملف أكبر من 5MB



```bash**الحل**:

curl -X PUT http://localhost:5000/api/contact/507f1f77bcf86cd799439011 \

  -H "Authorization: Bearer <token>" \- استخدم صور أصغر

  -H "Content-Type: application/json" \- اضغط الصور قبل الرفع

  -d '{

    "email": "contact@example.com",---

    "phone": "+1-555-123-4567",

    "address": "123 Main St, City, Country",## 🔧 المتغيرات البيئية المهمة

    "city": "New York",

    "country": "United States"| المتغير       | الافتراضي                                   | الوصف                               |

  }'| ------------- | ------------------------------------------- | ----------------------------------- |

```| `MONGODB_URI` | `mongodb://localhost:27017/portfolio-admin` | رابط قاعدة البيانات                 |

| `PORT`        | `5000`                                      | منفذ الخادم                         |

---| `JWT_SECRET`  | -                                           | مفتاح سري للتوقيع الرقمي (مهم جداً) |

| `NODE_ENV`    | `development`                               | بيئة التطوير/الإنتاج                |

## 🐛 Troubleshooting| `CORS_ORIGIN` | `http://localhost:4200`                     | الأصل المسموح به                    |



### Error: `ECONNREFUSED - Connection Refused`---

**Meaning**: Cannot connect to MongoDB

## 📋 قائمة المكتبات المستخدمة

**Solution**:

```bash| المكتبة               | الإصدار      | الاستخدام                       |

# Check if MongoDB is running| --------------------- | ------------ | ------------------------------- |

mongod| **express**           | ^4.18.2      | إطار العمل الرئيسي              |

| **mongoose**          | ^7.5.0       | التواصل مع MongoDB              |

# Verify MONGODB_URI in .env| **bcryptjs**          | ^2.4.3       | تشفير كلمات المرور              |

# Default: mongodb://localhost:27017/portfolio-admin| **jsonwebtoken**      | ^9.0.2       | إنشاء والتحقق من JWT            |

```| **dotenv**            | ^16.3.1      | إدارة المتغيرات البيئية         |

| **cors**              | ^2.8.5       | السماح بطلبات CORS              |

### Error: `Port already in use`| **express-validator** | ^7.0.0       | التحقق من البيانات المدخلة      |

**Meaning**: Another process is using port 5000| **multer**            | ^1.4.5-lts.1 | رفع الملفات                     |

| **nodemon**           | ^3.0.1       | إعادة تشغيل تلقائية (تطوير فقط) |

**Solution**:

```bash---

# Change port in .env

PORT=5001## 🚀 نصائح الإنتاج



# Or find and kill the process using port 5000### قبل النشر إلى الإنتاج:

# On Windows:

netstat -ano | findstr :50001. **غير `JWT_SECRET`** إلى مفتاح قوي وعشوائي

taskkill /PID <PID> /F

```bash

# On Mac/Linux:# توليد مفتاح عشوائي قوي:

lsof -i :5000node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"

kill -9 <PID>```

````

2. **استخدم MongoDB Atlas** بدلاً من MongoDB محلي

### Error: `Invalid token`3. **فعّل HTTPS** على الخادم

**Meaning**: JWT token is invalid, expired, or malformed4. **حدّد `CORS_ORIGIN`** للنطاق الفعلي

5. **استخدم متغيرات البيئة** لجميع المعلومات الحساسة

**Solution**:6. **فعّل تسجيل الأخطاء** (Logging)

- Login again to get a new token7. **استخدم Helmet** لحماية الرؤوس

- Ensure token is sent correctly in Authorization header8. **حدّد حدود معدل الطلبات** (Rate Limiting)

- Check that JWT_SECRET matches between server and token generation

---

### Error: `File too large`

**Meaning**: Uploaded file exceeds 5MB limit## 📚 موارد إضافية

**Solution**:- [Express.js Documentation](https://expressjs.com/)

- Compress images before upload- [MongoDB Documentation](https://docs.mongodb.com/)

- Use smaller image sizes- [Mongoose Documentation](https://mongoosejs.com/)

- Check file dimensions and quality- [JWT Introduction](https://jwt.io/)

- [bcryptjs Documentation](https://github.com/dcodeIO/bcrypt.js)

### Error: `CORS error`

**Meaning**: Frontend domain is not allowed---

**Solution**:## 📧 التواصل والدعم

````env

# Update CORS_ORIGIN in .envللأسئلة والدعم:

CORS_ORIGIN=http://localhost:4200

# Or use the exact frontend URL in production- 📧 البريد الإلكتروني: support@example.com

```- 🐛 الإبلاغ عن الأخطاء: [GitHub Issues](https://github.com/your-username/portfolio-backend/issues)

- 💬 النقاشات: [GitHub Discussions](https://github.com/your-username/portfolio-backend/discussions)

---

---

## 🔧 Important Environment Variables

## 📜 الترخيص

| Variable | Default | Description |

|----------|---------|-------------|هذا المشروع مرخص تحت رخصة ISC.

| `MONGODB_URI` | `mongodb://localhost:27017/portfolio-admin` | Database connection string |

| `PORT` | `5000` | Server port |```

| `JWT_SECRET` | - | Secret key for JWT signing (CRITICAL) |ISC License

| `NODE_ENV` | `development` | Environment (development/production) |

| `CORS_ORIGIN` | `http://localhost:4200` | Allowed frontend URL |Copyright (c) 2024



---Permission to use, copy, modify, and/or distribute this software for any

purpose with or without fee is hereby granted, provided that the above

## 📋 Dependenciescopyright notice and this permission notice appear in all copies.

````

| Package | Version | Purpose |

|---------|---------|---------|---

| **express** | ^4.18.2 | Web framework |

| **mongoose** | ^7.5.0 | MongoDB ODM |<p align="center">

| **bcryptjs** | ^2.4.3 | Password hashing | <strong>تم إنشاء هذا المشروع بـ ❤️</strong><br>

| **jsonwebtoken** | ^9.0.2 | JWT creation/verification | <em>Portfolio Admin Control Panel Backend v1.0.0</em>

| **dotenv** | ^16.3.1 | Environment variable management |</p>

| **cors** | ^2.8.5 | CORS middleware |
| **express-validator** | ^7.0.0 | Input validation |
| **multer** | ^1.4.5-lts.1 | File upload handling |
| **nodemon** | ^3.0.1 | Development auto-reload |

---

## 🚀 Production Deployment Checklist

Before deploying to production:

- [ ] Change `JWT_SECRET` to a strong random value
  ```bash
  node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"
  ```
- [ ] Use MongoDB Atlas or managed MongoDB service
- [ ] Enable HTTPS/SSL certificate
- [ ] Set `CORS_ORIGIN` to production domain
- [ ] Set `NODE_ENV=production`
- [ ] Add rate limiting middleware
- [ ] Enable request logging
- [ ] Use process manager (PM2)
- [ ] Set up monitoring and alerting
- [ ] Regular database backups
- [ ] Keep dependencies updated

### Deployment with PM2:

```bash
npm install -g pm2

# Start with PM2
pm2 start server.js --name "portfolio-api"

# Save PM2 configuration
pm2 save

# Enable PM2 startup
pm2 startup
```

---

## 🔒 Security Best Practices

1. **Keep Dependencies Updated**

   ```bash
   npm audit
   npm audit fix
   ```

2. **Never Commit `.env` File**

   ```bash
   echo ".env" >> .gitignore
   ```

3. **Use HTTPS in Production**

   - Obtain SSL certificate
   - Redirect HTTP to HTTPS

4. **Input Validation**

   - All endpoints validate input
   - Use express-validator

5. **Rate Limiting**

   - Implement for authentication endpoints
   - Prevent brute force attacks

6. **CORS Configuration**

   - Specify exact origins
   - Limit methods and headers

7. **Database Security**
   - Use strong passwords
   - Enable authentication
   - Regular backups

---

## 📚 Additional Resources

- [Express.js Documentation](https://expressjs.com/)
- [MongoDB Documentation](https://docs.mongodb.com/)
- [Mongoose Documentation](https://mongoosejs.com/)
- [JWT Introduction](https://jwt.io/)
- [bcryptjs GitHub](https://github.com/dcodeIO/bcrypt.js)
- [Node.js Best Practices](https://nodejs.org/en/docs/guides/)

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📧 Support

For issues, questions, or suggestions:

- 📧 Email: support@example.com
- 🐛 Report Issues: [GitHub Issues](https://github.com/your-username/portfolio-backend/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/your-username/portfolio-backend/discussions)

---

## 📜 License

This project is licensed under the ISC License - see the LICENSE file for details.

```
ISC License

Copyright (c) 2024

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.
```

---

<p align="center">
  <strong>Built with ❤️ for Portfolio Management</strong><br>
  <em>Portfolio Admin Control Panel Backend v1.0.0</em>
</p>

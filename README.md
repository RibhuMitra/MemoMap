# 🗺️ MemoMap  

MemoMap is a **Flutter + Supabase** powered application that lets users **upload images with descriptions and locations**.  
Every memory is securely tied to a user account through authentication, so each user manages their own private collection.  

---

## ✨ Features  
- 📸 Upload images directly from your device  
- 📝 Add descriptions for each image  
- 📍 Attach location details (entered manually by the user)  
- 🔐 Secure user authentication (sign up, login, logout)  
- 🗄️ Store metadata (description + location) in Supabase database  
- ☁️ Store images in Supabase Storage, linked to each user  
- 🌐 Cross-platform (Android, iOS, Web, Desktop)  

---

## 🛠️ Tech Stack  
- **Frontend:** Flutter (Dart)  
- **Backend & Auth:** Supabase  
- **Database:** PostgreSQL (via Supabase)  
- **Storage:** Supabase Storage  

---

## 🚀 Getting Started  

### 1️⃣ Prerequisites  
- [Flutter SDK](https://flutter.dev/docs/get-started/install) installed  
- [Supabase Project](https://supabase.io) created  
- Supabase credentials (`SUPABASE_URL` & `SUPABASE_ANON_KEY`)  

### 2️⃣ Clone Repository  
```bash
git clone https://github.com/RibhuMitra/MemoMap.git
cd MemoMap

flutter pub get

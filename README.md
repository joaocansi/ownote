# 📝 ownote

A markdown-based notes application with permanent publishing. Once published, notes cannot be deleted or modified.

## 🛠️ Tech Stack

- **Backend**: Go with Gin
- **Frontend**: Next.js 14
- **Database**: SQLite
- **Styling**: Tailwind CSS

## 🚀 Quick Start

### Backend

```bash
cd backend
go mod download
go run main.go
```

Server runs on `http://localhost:8080`

### Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on `http://localhost:3000`

## 📋 Usage

1. ✍️ Write your note in markdown
2. 👀 Preview in real-time
3. 🏷️ Add tags (optional)
4. 📤 Click "Publish" (permanent action)

## 📁 Project Structure

```
ownote/
├── backend/     # Go API server
├── frontend/    # Next.js app
└── README.md
```

## 📄 License

MIT

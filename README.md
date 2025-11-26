# 📒 NotesFlow — Simple Notes App

NotesFlow adalah aplikasi pencatatan sederhana berbasis **Kotlin + Jetpack Compose + MVVM + Room**.  
Aplikasi ini memungkinkan pengguna untuk menambahkan, melihat, mengedit, dan menghapus catatan secara offline.

---

## 🚀 Features
- Add new note  
- View notes list  
- Edit existing note  
- Delete note  
- Offline storage using Room Database  

---

## 🛠 Tech Stack
| Layer | Technology |
|-------|------------|
| Language | Kotlin |
| UI | Jetpack Compose + Material 3 |
| Architecture | MVVM + Repository |
| Local Storage | Room Database |
| State | StateFlow |

---

## 📂 Project Structure
```
data/
└── local/
├── NoteDao.kt
├── NoteDatabase.kt
└── NoteRepository.kt
domain/
└── Note.kt
ui/
├── NoteViewModel.kt
└── screens/
├── NotesScreen.kt
├── AddNoteScreen.kt
```


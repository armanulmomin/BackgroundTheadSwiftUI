
## 🛠 Technologies Used

- **Swift** (Concurrency with GCD)
- **SwiftUI** (Declarative UI)
- **DispatchQueue** (Main & Background)
- **URLSession** (Network Requests)

## 📖 How It Works

1. **Background Thread for Data Fetching**  
   Data fetching is done using:
   ```swift
   DispatchQueue.global(qos: .userInitiated).async {
       print("Is Main Thread? \(Thread.isMainThread)")
       print("Current Thread: \(Thread.current)")
       // Fetch data here...
   }
## screenshots
<img width="1094" height="723" alt="Thread 1" src="https://github.com/user-attachments/assets/713bb625-922a-4079-b3c2-b251f8cc05aa" />
<img width="458" height="978" alt="Thread 2" src="https://github.com/user-attachments/assets/edb01772-a8e9-4145-b3c4-b497c6b80aee" />

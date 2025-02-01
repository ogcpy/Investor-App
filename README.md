📱 Seller Financing Calculator
A simple iOS app built with SwiftUI to calculate annual payments for seller-financed loans.

🚀 Features
✅ User-friendly UI for entering loan details
✅ Calculates annual payments instantly
✅ Responsive design optimized for iPhones
✅ Built using Swift and SwiftUI

🖼️ Screenshots
(Add screenshots of your app here once you test it on your iPhone)

📂 Project Structure
bash
Copy
Edit
SellerFinancingApp/
│── SellerFinancingApp.xcodeproj  # Xcode project file
│── SellerFinancingApp/
│   │── ContentView.swift         # Main UI and logic
│   │── SellerFinancingAppApp.swift  # App entry point
│   └── Assets.xcassets            # Image and color assets
│── Preview Content/
│── README.md                      # Project documentation
└── .gitignore                      # Git ignore file
🛠️ Installation
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/ogcpy/Investor-App.git
cd SellerFinancingCalculator
2️⃣ Open in Xcode
Open SellerFinancingApp.xcodeproj in Xcode.
Ensure you have Xcode 15+ installed.
3️⃣ Run on iPhone Simulator
Select an iPhone device from the Xcode toolbar.
Click Run (▶) button to launch the app in the simulator.
4️⃣ Install on Your iPhone
Connect your iPhone via USB.
Enable Developer Mode:
Go to Settings → Privacy & Security → Developer Mode → Enable.
Select your iPhone as the target device in Xcode.
Click Run to install the app.
📜 Usage
Enter the Total Purchase Price (£).
Enter the Annual Interest Rate (%).
Enter the Number of Years for financing.
Click "Calculate Annual Payment" to see results instantly.
💻 Code Overview
🔹 UI Layout (ContentView.swift)
Uses VStack for structured layout.
TextField elements for user input.
Button to trigger the calculation function.
🔹 Loan Calculation Logic
The function calculatePayment() uses the formula:

𝐴
=
𝑃
⋅
𝑟
⋅
(
1
+
𝑟
)
𝑛
(
1
+
𝑟
)
𝑛
−
1
A= 
(1+r) 
n
 −1
P⋅r⋅(1+r) 
n
 
​
 
Where:

P = Principal Amount
r = Annual Interest Rate (as a decimal)
n = Number of Years
🎨 UI Preview
You can see a live preview in Xcode using the SwiftUI PreviewProvider.

swift
Copy
Edit
struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
}
🚀 Future Improvements
✅ Add Monthly Payment Calculation
✅ Include Customizable Loan Terms
✅ Implement Dark Mode Support
✅ Save User Input History
🛠️ Technologies Used
Swift
SwiftUI
Xcode
👨‍💻 Contributing
Want to improve this project? Contributions are welcome! 🚀

Fork the repo
Create a new branch (feature/your-feature)
Commit your changes
Push to your branch and create a PR
📄 License
This project is licensed under the MIT License – feel free to use and modify it!

📧 Contact
For questions or collaboration, reach out via:
🐦 Twitter: @bashdavidson

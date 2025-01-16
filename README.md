# Demo on Student Attendance project on Aleph Zero

This project is a simple demo on how to deploy a small smart contract project on Aleph Zero Testnet

# To Understand the basic file structure and code

```bash
git clone https://github.com/WallstreetDAO-KLH/Student_attendance_demo_Rust_Azero
cd Student_attendance_demo_Rust_Azero
cargo install cargo-contract
cargo contract build
```

once the contract is built you can hover to the attendance_register\target\ink\attendance_register.contract . And copy it and put it on the Aleph zero  developer portal.

# file structure
```bash
attendance_register/
├── Cargo.toml
└── src/
    └── lib.rs
```
# images:

![image](https://github.com/user-attachments/assets/bf786f68-3ef9-4028-a7f5-85a4dc5c20b6)
![image](https://github.com/user-attachments/assets/e67966a7-6853-494a-907f-0d73b97a13c5)
![image](https://github.com/user-attachments/assets/327db611-ac96-4117-ad3a-0f4e4e88ca1b)

# link

contract deployment : https://ui.use.ink/add-contract
testnet faucet : https://faucet.test.azero.dev/

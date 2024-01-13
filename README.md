# Grocery-Store

<h1 align="center">
<img align="center" height="80px" width="80px" src="https://github.com/iamwilldev/Kumpulan-Dataset/blob/cc67a9a3c8f5704a8f63832db0adc7b21c24aec7/Github/kai.png" alt="Kai-icon">
 Kai
</h1>
<p align="center">
This is a grocery store desktop application for stock, customer, and cashier management.
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#building-from-source">Building from source</a> •
  <a href="#support">Support</a> •
</p>

![image](https://github.com/iamwilldev/Kumpulan-Dataset/blob/cc67a9a3c8f5704a8f63832db0adc7b21c24aec7/Github/login.png)

## Admin Menu

| Manage Pengguna                                                                                                                                                                           | Manage Barang                                                                                                                                                                             |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="500" src="https://github.com/iamwilldev/Kumpulan-Dataset/blob/cc67a9a3c8f5704a8f63832db0adc7b21c24aec7/Github/admin-managePengguna.png"> | <img width="500" src="https://github.com/iamwilldev/Kumpulan-Dataset/blob/cc67a9a3c8f5704a8f63832db0adc7b21c24aec7/Github/admin-manageBarang.png"> |

| Manage Supplier                                                                                                                                                                           | Manage Customer                                                                                                                                                                           |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="500" src="https://github.com/iamwilldev/Kumpulan-Dataset/blob/cc67a9a3c8f5704a8f63832db0adc7b21c24aec7/Github/admin-manageSupplier.png"> | <img width="500" src="https://github.com/iamwilldev/Kumpulan-Dataset/blob/cc67a9a3c8f5704a8f63832db0adc7b21c24aec7/Github/admin-manageCustomer.png"> |

## Petugas Menu

| Grocery Store                                                                                                                                                                             | Cart                                                                                                                                                                                    |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="500" src="https://github.com/iamwilldev/Kumpulan-Dataset/blob/cc67a9a3c8f5704a8f63832db0adc7b21c24aec7/Github/GroceryStore.png"> | <img width="500" src="https://github.com/iamwilldev/Kumpulan-Dataset/blob/cc67a9a3c8f5704a8f63832db0adc7b21c24aec7/Github/Cart-GroceryStore.png"> |

| Customer Area                                                                                                                                                                             |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img width="500" src="https://github.com/iamwilldev/Kumpulan-Dataset/blob/cc67a9a3c8f5704a8f63832db0adc7b21c24aec7/Github/petugas-customerArea.png"> |

## Features

- Login
- Manage Barang
- Manage Pengguna
- Manage Barang
- Manage Supplier
- Manage Customer
- Manage Transaksi
- Manage Cart
- Manage Customer Area
- 2 Role (Admin dan Petugas)

1. **Admin**
   Username: admin
   Password: admin

2. **Petugas**
   Username: petugas
   Password: petugas

## Building from Source

Ensure you have [Python 3.11.5](https://www.python.org/downloads/) and [Git](https://github.com/git-guides/install-git) installed.

Open a terminal and run the following commands.

1. **Set everything up.**

- Linux/Mac

```
git clone https://github.com/iamwilldev/Grocery-Store && cd Grocery-Store && python -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt
```

- Windows (Command Prompt)

```
git clone https://github.com/iamwilldev/Grocery-Store && cd Grocery-Store && python -m venv .venv && .venv\Scripts\activate && pip install -r requirements.txt
```

2. **Build the app into an executable.**

```
pip install cx_freeze==6.15.10 && python main.py build
```

## Support

- You can support the development of Grocery-Store through donations on [GitHub Sponsors]().
- You can also leave a star on the github for more weebs to know about it.
- Grocery-Store is open to pull requests, so if you have ideas for improvements, feel free to contribute!

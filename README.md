# Loan Qualifier New Feature!

Here at Bizops with the recent success of our new loan qualifier application we have decided to add a new feature. This feature now allows customers to have the option to save their qualifying loans into CSV file format for personal use. 

---

## *Technologies*

- **Programming Language:** Python 3.9.13
- **Libraries:** Fire, Questionary, Sys, Pathlib
- **Framework:** VS Code
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*

Before running the program, ensure your operating system has at least version 3.9.13 of Python installed, ensure Visual Studio Code is installed, and ensure Python Fire and Python Questionary are installed. Then, you will clone the repo onto your local computer in VS Code.

- To check your computer's current Python version, in terminal, run: ![python_version](https://user-images.githubusercontent.com/123714457/228030721-8905ed97-ad3a-40af-96ec-078a6492fb56.png)
- If you do not have python installed: [Download Python](https://www.python.org/downloads/)
- If you do not have VS Code installed: [Setting up VS Code](https://code.visualstudio.com/docs/setup/setup-overview)
- To install Fire from pypi, in terminal run: ![pip_fire](https://user-images.githubusercontent.com/123714457/228030808-a5269f51-9e1a-4955-bc5f-3fcc63f594f0.png)
- To install Questionary from pypi, in terminal run: ![pip_quest](https://user-images.githubusercontent.com/123714457/228030876-5ad76caa-d23a-4c5a-bf15-f783c7c2cd4c.png)
- Copy URL of GitHub repo: github.com/djohnst914/Loan_Qualifier_New_Feature
- Open VS Code, select 'Clone Git Repository...', paste URL into repository URL input and hit enter <img width="120" alt="Screenshot 2023-03-28 at 12 33 17 PM" src="https://user-images.githubusercontent.com/123714457/228347670-06762756-eea5-4deb-8044-ef5198c381f8.png"> --> <img width="250" alt="Screenshot 2023-03-28 at 12 33 29 PM" src="https://user-images.githubusercontent.com/123714457/228347723-b1735963-de94-4e4f-a87e-522f8debf280.png"> --> <img width="200" alt="Screenshot 2023-03-28 at 12 32 36 PM" src="https://user-images.githubusercontent.com/123714457/228347773-220590b4-db20-407b-8cd0-6a2814549107.png">
- Select preferred repository destination and save
- Double check if the Fire and Questionary imports at the top of the main app are loading correctly. If not, check your selected python version in the bottom right of the screen. Reference these images as example:
<img width="250" alt="import_3 11" src="https://user-images.githubusercontent.com/123714457/228351232-35278eb5-8c63-4057-a4e0-00bc1ed05e80.png"> <img width="250" alt="import_3 9" src="https://user-images.githubusercontent.com/123714457/228351240-35e3f24d-7091-4033-bf04-a26e6315cbc4.png">
---

## *Usage*

- **1:** In terminal cd to directory where newly downloaded app.py resides. Type and enter ![Screenshot 2023-03-28 at 12 55 06 PM](https://user-images.githubusercontent.com/123714457/228352291-7322d0ca-9074-4e0c-91f7-16a989f77250.png)
- **2:** The program will ask to input file path, type and enter: ![Screenshot 2023-03-28 at 12 57 39 PM](https://user-images.githubusercontent.com/123714457/228352839-ca869079-8d81-4d87-b784-0fc3f3d28d5e.png)
- **3:** The program will ask series of questions determining what loans you qualify for: 
![Screenshot 2023-03-28 at 1 00 43 PM](https://user-images.githubusercontent.com/123714457/228353884-0ddf37b2-5d07-4af2-a1c0-889795388a79.png)
- **4:** If you do not qualify for any loans the program will exit with a message. Otherwise, it will give you some information then ask if you'd like to save the results of the loans you qualfied for. This being the new feature of the application and considering you would like to save the results, enter yes
- **5:** Program will ask you to specify a file path to save qualifying data. Remember, after specifying location to give new list a name ending with .csv. Program will end with a message: ![Screenshot 2023-03-28 at 1 27 43 PM](https://user-images.githubusercontent.com/123714457/228359082-bd69c3e1-eb71-44e5-ad34-5745a605fdf5.png)
- **Note:** You can access your newly saved list of banks in the location you saved it in!

## *Contributors*

- Dylan Johnston
- Email: dylanhjjohnston@gmail.com

---

## *License*

This software is licensed under GNU General Public License v3.0. See the [LICENSE](https://github.com/djohnst914/Loan_Qualifier_New_Feature/blob/main/LICENSE) file for details. 
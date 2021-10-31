<h1 align="center">PyChain Ledger</h1>

Conducting business with other banks is a given in the banking industry. Between sending and receiving money, each bank needs checks and balances, or a reconciliation process, to ensure they are sending and receiving the correct amount. The purpose behind the Pychain Ledger was to build a blockchain-based ledger system to allow partner banks to conduct financial transactions with the ability to verify the integrity of the data. With this type of technology, we are innovating and making reconciling tasks more efficient for both parties.

## Technologies

In order for this program to run, this application must be used in either Git Bash or VS Code, as it uses the Python language. To run the program, it is essential to have Anaconda/Python installed. To ensure the code works, please open the file in a dev environment using python.

The operating systems and program versions are mentioned below and are highly recommended when running the program.

**Systems**

[conda 4.10.3](https://docs.anaconda.com/anaconda/install/index.html) - Package manager, Environment Manager

python 3.7 - included in Anaconda

[Pandas](https://pandas.pydata.org/) - Open source data analysis and manipulation tool

**Other Installations**

[Streamlit](https://github.com/streamlit/streamlit) - Open source app framework

---

## Installation Guide


As mentioned above, to ensure that there are no errors when running this application, the user must use Git Bash or Visual Studio Code to access the application file. 

For this application, the user may need to downgrade their previous program installations. Please be sure to use the versions below:

```
pip uninstall pandas -y
pip install pandas==1.2.5

pip uninstall streamlit -y
pip install streamlit==0.84.2

```

WARNING: Pandas 1.3.0 or greater is not compatible with Streamlit.

---

## Usage

From the GitBash terminal, the user can open the application by entering the following code:

![image](https://user-images.githubusercontent.com/84649228/139596854-0ac539b0-ff06-4dab-8870-7a3508f85173.png)

A new web browser will open to the Pychain Ledger.

![image](https://user-images.githubusercontent.com/84649228/139596887-014be0fd-9868-4a1c-b1c6-0482302c8865.png)

Enter in all the data, and as you will see, all the data blocks enter will keep growing and building up. 
![image](https://user-images.githubusercontent.com/84649228/139553498-f37e56f9-8eb2-4214-b598-70d327ed2f56.png)

You can even use the side bar "Block Inspector" to investigate certain blocks and look at the detail. 

![image](https://user-images.githubusercontent.com/84649228/139552725-417a0e12-c6e7-480b-a863-3fd852585cf2.png)
![image](https://user-images.githubusercontent.com/84649228/139552932-86405f97-ca54-41ba-921e-ccb7d59c70f1.png)

To verify the information is correct, click on the "Validate Chain" to see if all blocks in the ledger are legit. If the answer comes back "True" they are legitimate.

![image](https://user-images.githubusercontent.com/84649228/139552388-89cfa812-a87c-493c-965f-832bf560d2b4.png)

## Contributors

[Julia Guanzon](www.linkedin.com/in/julia-guanzon)

## License

MIT License



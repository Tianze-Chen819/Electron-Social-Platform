# LGBTQ Social Platform

A prototype desktop app built with Electron to connect LGBTQ+ users through matching, chatting, and location-based discovery.

---

## Getting Started


### 1. Install Node.js

Download and install Node.js (includes npm):  
👉 https://nodejs.org/en/download

Then open Terminal and check versions:

```bash
node -v
npm -v
```

### 2. Clone the Repository

```bash
git clone https://github.com/Tianze-Chen819/LGBTQ-Social-Platform.git
cd LGBTQ-Social-Platform
```

### 3. Install Project Dependencies

``` bash
npm install
```
### 4. Run the App

```bash
npm start
```



## 📁Project Structure

File Folder	    Purpose
index.html	    Main interface: swipe, chat, map  
main.js	        Logic for Electron app and interaction  
package.json	  Project config: dependencies & entry file  

## 🧑‍💻How to Edit

Open the project folder using Visual Studio Code  
Modify index.html for layout and UI  
Modify main.js for logic and behavior  

## ✨Features

Match users with swipe cards (left/right)  
Auto-reply bots with chat bubbles  
User avatars on a map with tags  
Modern, app-like theme and animations  

## 🙋‍♂️ Maintainer
Tianze Chen  
GitHub: @Tianze-Chen819  

## 👥 Collaborators

- Tianze Chen  
- Haojing Gao  
- Yuan Tao  


## ✅ How to Commit and Push Changes (Step-by-step)
After editing code:  
1. Save your changes in VS Code
 ❕❕❕每次上传时不要上传node_modules文件夹，这个文件夹是运行软件的dependencies超出100MB
      可以直接删掉这个文件夹再进行下面操作（下一次打开时npm install的时候会再此下回来）。    
3. In Terminal, make sure you're in the project folder:  
```bash
cd ~/Desktop/LGBTQ-Social-Platform
```
3. Stage all your changes:
```bash
git add --all
```
4. Commit your changes:
```bash
git commit -m "Describe what you changed"
```
Example:
```bash
git commit -m "Fix layout of match cards"
```
5. Push to GitHub:
```bash
git push
```

6. ✅(不推荐的做法，会删掉原本的branch最好在进行操作前通知别的collaborators) 如果不小心node_modules被commit然后在push的时候卡住可以进行一下操作  
   （1）control + C 终止push  
   （2）在文件夹中删掉node_modules  
   （3）运行以下代码  
   ``` bash
   git checkout --orphan latest-clean
   git add -A
   git commit -m "Clean history"
   git branch -D main
   git branch -m main
   git push -f origin main
   ```

## 💡 Tips for Collaborating
Always run git pull before starting work each day  
Write short, clear commit messages  
Ask if unsure before deleting or renaming files  

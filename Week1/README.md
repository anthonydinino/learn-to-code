# Week 1

## **Your Code Editor**

### Download VSCode

- Ensure "Add to PATH" is ticked

- Download Prettier extension for automatic code formatting

- Download ESLint extension to check for errors automatically in your code.

_Answer Questions_

## **Navigate Terminal**

Open your terminal

`cd` - is your current directory

- Root Directory is `C:/`
- Home Directory is `C:/Users/JohnSmith`

Change your current directory to your home directory by using the `~` shortcut.

```
cd ~
```

This is the equivilant to

```
cd C:\Users\JohnSmith
```

For the root directory it's just

```
cd \
```

_Answer Questions_

## **Setting Up A Project**

Create a folder using this command.

```
mkdir ~/Work
```

This will create a folder inside your home directory called `Work`

`cd` into that folder

## **Installing NPM**
NPM allows us to use 3rd party (other people's) code easier. It's heavily used for React/ JavaScript stuff.

### Linux
Install NVM
```
https://github.com/nvm-sh/nvm#installing-and-updating
```
Run:
```
nvm install --lts
```

### Windows
https://nodejs.org/en/download/


## **Installing GIT**

### Linux

```
sudo apt install git-all
```

### Windows

https://git-scm.com/download/win

_Answer Questions_

## **Open VSCode from terminal**

```
code .
```

The dot (`.`) is a reference to your current directory.

Below is also the equivilant.

```
code ~/Work/test-project
```

VSCode should automatically open.

Press `CTRL + ~` to automatically open terminal within VSCode.

_Answer Questions_

## **Initialise React Project**

Make  `~/Work` your current directory 

```
npm create vite@latest
```
>Vite is a build tool used to build multiple things together including React

Follow the prompts using information below:

```
Project Name: react-test
Framework: React
Variant: JavaScript
```

Eventually you will see:

```
Done. Now run:

  cd react-test
  npm install
  npm run dev
```

Run the above commands in order.

- `cd react-test` changes your current directory to your new project directory that vite built for us.
- `npm install` installs all 3rd party packages in a `node_modules` folder inside your project folder. All these packages (dependencies) are listed in the `package.json` 
- `npm run dev` runs the `vite` command as shown in the `package.json` under scripts. This command is used to host the project locally on your computer while your developing, also giving you instantaneous feedback.

Go to `http://localhost:5173/` in your browser to see the an example React site in action!

> `http://localhost:\<port number\>` is very commonly used while doing development work. It's like a personal server that only your computer can access. The port number at the end `:5173` is somewhat random and can differ with different tools.

## **END WEEK 1**




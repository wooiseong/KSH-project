# :house_with_garden:	 KSH hostel :house_with_garden:	

Thus is a website where you can search hostels located in Kaohsiung, Taiwan. Moreover, you can register a new account and login to upload your profile picture and change your password.

Demo here :point_down: <p></p>
<a href="https://ksh-project-vercel-1.vercel.app/"><img src="https://img.shields.io/badge/link-KSH.hostel-1?style=flat&logoColor=red&labelColor=%237B7B7B&color=%23FFDA6A" alt="KSH.hostel"></a>

## Project View
Desktop (1366px)

![image](https://i.ibb.co/1Xyx46B/1-header-before-Login.png)

You can click on this link to view more pictures :point_right::point_right::point_right: 
<a href="https://drive.google.com/drive/folders/16bUqu92zvwPCL3W7V19hLtldLZySoecc?usp=sharing">KSH hostel</a>

## Features
|          Components               | Description                                                  | URL                  |
| :--------------------------: | ------------------------------------------------------------ | -------------------- |
|    Home    | 1. A searchBar is provided for users to view hostels in Kaohsiung <br>2. Users can obtain more details about interested hostels by clicking the toggle icon | /      |
|      Login       | 1. Users can switch login and register form <br>2. Users will receive warning if the input is not valid 3. Users will be notified about the result of form submission| /login.html         |
|      Account        | 1. Section A - Users can preview, cancel and upload profile picture (type: ico, jpg, jpeg, png) <br>2. Section B - Users can change password for their account | /account.html         |


## Tools
1. Designs&nbsp; (&nbsp;Bootstrap + Sass&nbsp;)
2. Framework&nbsp; (&nbsp;Vue&nbsp;)
3. Building tool&nbsp; (&nbsp;Vite&nbsp;) 
4. Storage&nbsp; (&nbsp;Pinia&nbsp;)
5. Validation&nbsp; (&nbsp;Bootstrap validator + jQuery validate&nbsp;)
6. Backend&nbsp; (&nbsp;JSON Server&nbsp;)
7. Deployment&nbsp; (&nbsp;Vercel&nbsp;)
8. Code check&nbsp; (&nbsp;husky + lint-staged&nbsp;)

## Bugs/Future plans
1. The large circle of customized cursor (plugin-GSAP) is not appeared during the first load of this project, until the page is refreshed. I will figure it out or change another cursor animation.

## Installation
Please follow the instructions to get a copy of this project.

### Prerequisites
 * <a href="https://pnpm.io/installation">pnpm</a> 

### Clone
```sh
git clone https://github.com/wooiseong/sleepPower-project.git
```

### Install pnpm packages
```sh
pnpm install
```

### Compile and Hot-Reload for Development

```sh
pnpm dev
```

### Compile and Minify for Production

```sh
pnpm build
```

### Lint with [ESLint](https://eslint.org/)

<h1 align="center">Unreal Engine 5 for Beginners, First Edition</h1>
<p align="center">This is the code repository for <a href ="https://www.amazon.com/Unreal-Engine-Beginners-step-step/dp/1806105918"> Unreal Engine 5 for Beginners</a>, published by Packt.
</p>

<h2 align="center">
A step-by-step guide to building your first playable third-person action game
</h2>
<p align="center">by Zhenyu George Li (Author), Charles Shih-I Yeh (Author), Michael Oakes (Author)</p>

<details open> 
  <summary><h2>What is this repository for?</summary>
<p>
This repository contains the Pangaea project for the book Unreal Engine 5 for Beginners.
Branches in this repository match the book's chapter content. Each chapter, except Chapter 1, has two branches:
* Start Branch (e.g., Chapter02-Start): Contains the game project and needed assets for starting the chapter
* Complete Branch (e.g., Chapter02): Contains the completed project after working through the chapter
Readers can download the Start branch at the beginning of a new chapter and follow the instructions in the book. The Complete branch can be used as a reference and to evaluate learning progress.
All required assets are placed in the */Pangaea\_Assets* folder, including 3D models, animations, textures, audio files, and more.     
</p>    
</details>

<details open>
  <summary><h2>Important Note to Use this Repo</summary>
   <p>This book is structured so that Chapters 1 through 7 introduce the essential knowledge needed to create a basic action game in Unreal Engine. Starting with Chapter 3, each chapter’s starting branch is nearly identical to the completed branch from the previous chapter. For example, the Chapter05 and Chapter06-Start branches contain essentially the same project.

Beginning with Chapter 8, you will apply what you learned in Chapters 1 through 7 to build a complete game. Therefore, the Chapter08-Start branch is not identical to the completed Chapter07 branch. In addition to introducing new enemy characters, the Chapter08-Start branch includes fixes for several minor issues.

We recommend using the corresponding Start branch at the beginning of each chapter. For example, when starting Chapter 3, use the Chapter03-Start branch. After completing the chapter, your project should match the content of the completed Chapter03 branch. When you move on to Chapter 4, you can switch directly to the Chapter04-Start branch and continue following the instructions. If you encounter any problems during development, you can also download the completed Chapter03 branch separately and compare it with the changes you made while working through Chapter 3.

**If you have been using the same practice branch throughout Chapters 1 through 7, make sure you switch to the Chapter08-Start branch before beginning Chapter 8. Alternatively, download the Chapter08-Start branch into a separate local folder and use it to continue reading and practicing how to integrate the different features of the Unreal Engine project.**</p> 
</details>

<details open> 
  <summary><h2>Assets Export Restriction Notice</summary>
<p>
The 3D models, textures, and animations included in this project are licensed from third-party providers (e.g., Adobe **Mixamo**, **TurboSquid** Standard Royalty-Free). These assets are provided here only as embedded Unreal Engine assets (.uasset files) to support the educational and demonstration purposes of this project.
Exporting, extracting, or redistributing these assets in raw formats (such as .fbx, .obj, .png, etc.) outside of this project is not permitted under the respective licenses. If you wish to obtain the original files, please download them directly from the original sources: Adobe **Mixamo** and **TurboSquid**.
By using this project, you agree to respect these restrictions and to use the assets only within the context of this Unreal Engine sample project.    
</p>    
</details>

<details open> 
  <summary><h2>About the book</summary>
<a href="https://www.packtpub.com/en-ca/product/unreal-engine-5-for-beginners-9781806105908">
<img src="https://content.packt.com/_/image/original/B34284/cover_image.jpg" alt="Unreal Engine 5 for Beginners" height="256px" align="right">
</a>
<p>
Unreal Engine 5 for Beginners is a hands-on guide designed for aspiring developers, students, and hobbyists with little or no prior experience. Instead of overwhelming technical jargon, it takes a clear, step-by-step approach that helps readers quickly get comfortable with Unreal’s powerful tools. You’ll begin by installing Unreal Engine, setting up your first project, and exploring the editor to build and light simple levels. As you progress, you’ll learn how to script gameplay with Blueprints, create characters with animations, and set up player inputs for smooth control. Later chapters introduce AI-driven enemies, gameplay rules, and mission objectives that bring your world to life. The book also covers building user interfaces with UMG, producing cinematic cutscenes using Sequencer, and adding polish with visual and audio effects. Finally, you’ll learn optimization techniques and packaging workflows to prepare your game for distribution. By the end of this book, you’ll have built a fully playable third-person game and gained a solid foundation in Unreal Engine 5. Whether you want to create interactive 3D experiences, prepare for more advanced projects, or take the first step toward a career in game development, this guide gives you the confidence and skills to begin your journey.
</p>
</details>


<details> 
  <summary><h2>Get to know Authors</h2></summary>

_Zhenyu George Li_ Zhenyu George Li is a passionate video game developer with over 20 years of experience in the field. As a seasoned software engineer, George has contributed significantly to the development of numerous games throughout his career and currently serves as a senior development engineer at Unity.
George's fascination with video games was sparked during his college studies, igniting a passion that would shape his professional journey. During the early stages of his game development endeavors, George immersed himself in technologies such as Visual Basic, C/C++, DirectX, OpenGL, Windows GUI, SQL, and so on. These foundational experiences laid the groundwork for his subsequent success in the industry.
Throughout his career, George has made substantial contributions to various commercial games. Notable titles on his portfolio include Unity demo and starter kit games, Sandbox, Halo Infinite, Magic Arena, Stela, Dead Rising 2, The Bigs 2, and others. His involvement in these projects has allowed him to gain extensive knowledge and practical experience in a wide range of domains, including programming, game engines, gameplay and AI, graphics, animation, multiplayer, game physics, frontend, and multiplatform. In practical applications, George has used Unreal, Unity, and some propriety game engines in the development of real game projects.
In addition to his achievements as a game developer, George has also honed his teaching abilities during his eight years of college-level instruction. He has shared his knowledge and expertise with aspiring developers, serving as a lecturer at the Vancouver Film School, College of Interactive Arts, and Hefei Union University. While teaching at Vancouver Film School, George guided students through the intricacies of Unreal Engine, helping them build a strong foundation in professional game development.

_Charles Shih-I Yeh_ Charles Shih-I Yeh pursued his computer science studies at the University of Southern California before embarking on a career in the video game industry in the early 2000s. He has held various pivotal roles in game programming, including building proprietary game engines, crafting Digital Content Creation (DCC) tools to streamline production pipelines, and designing engaging gameplay mechanics alongside robust multiplayer and MMORPG tournament services.
Charles is also passionate and committed to sharing expertise and insights by delivering lectures on game programming at several esteemed universities. He is also the author of two game design books as well as the official translator of several famous game programming books, such as Game Programming Gems 4, into his native language, Mandarin.

_Michael Oakes_ Michael Oakes (BSc, PGDip, MSc) is an XR Specialist with Volvo, in Gothenburg, Sweden who previously worked in Games Development at Unity for 6 years. He has over a decade in games and 30 years in IT, and holds a Master’s degree in Computer Science with Games and Graphics Development from the University of Hull. 
Mikes expertise includes XR/VR/AR Design and Development, Shader Programming, AI, Software Engineering & Management, and Multiplayer Systems. 
Michael has also contributed as a technical consultant to books such as Unity Learn ML-Agents, Practical AI on the Google Cloud Platform, Unreal Engine 5 Game Development with C++ Scripting, and Practical C++ Game Programming with Data Structures and Algorithms.
</details>


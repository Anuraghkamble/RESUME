%-------------------------
% Resume in Latex
% Author : ETH juniors
% Inspired by: https://github.com/sb2nov/resume
% License : MIT
% Website : www.ethjuniors.ch
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{fontawesome5}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\input{glyphtounicode}

% Custom font
\usepackage[default]{lato}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting (Increased Font Size by 2pt)
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\Large
}{}{0em}{}[\color{black}\titlerule\vspace{-5pt}]

% Ensure that generated PDF is machine readable/ATS parsable
\pdfgentounicode=1

% Custom commands
\newcommand{\resumeItem}[2]{
  \item\small{
    \textbf{#1}{: #2 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{#3} & \textit{#4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
  \item
    \begin{tabular*}{\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textit{#1} & \textit{#2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item\small{
        \textbf{#1} \hfill \textnormal{#2 \vspace{-2pt}}
    }
}

\newcommand{\resumeSubItem}[2]{\resumeItem{#1}{#2}\vspace{-4pt}}

\renewcommand{\labelitemii}{$\circ$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%

%----------HEADING----------%
\begin{document}

\begin{center}
    \textbf{\Huge \scshape Kamble Anuragh} \\ \vspace{3pt}
     \small \href{mailto:kanuragh03@gmail.com}{kanuragh03@gmail.com} $|$+91-8374321303 $|$ Hyderabad, India \\[6pt]
    \href{https://www.linkedin.com/in/anuragh-kamble-9a848b294}{\faLinkedin} linkedin.com/in/anuraghkamble/\quad
    \href{https://github.com/Anuraghkamble}{\faGithub} github.com/anuraghkamble\quad
\end{center}

%-----------EDUCATION-----------%
\section{\hspace{0.3cm}Education}
\resumeSubHeadingListStart
  \resumeSubheading
    {Sreenidhi Institute Of Science And Technology}{ Hyderabad, India}
    {B. Tech Computer Science Engineering- Internet of Things 
  \hspace{0.3cm}CGPA: 7.75}{Oct 2022 -- Present}
    \resumeItemListStart
      \resumeItem{Subjects}
      {DBMS, Operating System, DSA, DCN, OOPs, IOT}
    \resumeItemListEnd
        
      \vspace{-20pt} 
     \resumeSubheading
    {Government Polytechnic Station Ghanpur}{ Jangaon, India}
    {Electrical and Electronics Engineering (Diploma)\hspace{0.3cm} Percentage: 80.8}{Jun 2019 -- May 2022}
    \resumeItemListStart
      \resumeItem{Subjects}
        {Mathematics, Digital Electronics, D.C. Machines }
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------PROJECTS-----------%
\section{\hspace{0.3cm}Projects}
  \resumeSubHeadingListStart
  \resumeProjectHeading
  {\textbf{Intelligent Gas Leakage Detector} $|$ \textnormal{Arduino IDE, Python, Firebase}}{Jan 2024 -- Jan 2024}
  \item[]
  An ESP-32 Microcontroller acting as CPU of the project and the Embedded sensors used to gather data and using various actuators gas leakage detection and controlling and also implemented real-time monitoring of the gas levels using cloud applications.

  \resumeProjectHeading
  {\textbf{ML-Based Diabetic Prediction} $|$ \textnormal{Python, NumPy, KNN Algorithm}}{Aug 2023 -- Sep 2023}
  \item[]
  A seminal advancement in predictive diabetic risk assessment, offering a tailored and data-driven approach specifically designed for women using ML.

  \resumeProjectHeading
  {\textbf{First-Person Exploration Game} $|$ \textnormal{C++, Unreal Engine 5, Blueprints}}{Dec 2022 -- Feb 2023}
  \item[]
  Developed a basic first-person exploration game using Unreal Engine, featuring interactive objects, simple AI, and a dynamic environment. Implemented character movement, collision detection, and a basic UI using Blueprints and C++.

%-----------SKILLS-----------%
\section{Technical Skills}
  \resumeSubHeadingListStart
    \resumeItem{Programming Languages}
      {C++, Java, Python, HTML, CSS }
    \resumeItem{Database Management}
      {MySQL}
    \resumeItem{Operating systems}
      {Windows, Linux}
    \resumeItem{Tools}
      {Git/Github, VS Code, Unreal Engine}
  \resumeSubHeadingListEnd

%-----------ACHIEVEMENTS-----------%
\section{Extra-Curricular Activities/Achievements}
  \resumeSubHeadingListStart
    \resumeItem{Class Representative}
    {Acted as a liaison between students and faculty, addressing academic and administrative concerns.}
    \resumeItem{Hackathons}
      {Participated in national level hackathon-HackSavvy-24, showcasing problem-solving abilities and teamwork.}
    \resumeItem{Volunteering}
      {Successfully conducted blood donation, cancer screening, and other health camps across colleges in Telangana state as part of Sreenidhi Cancer Foundation.}
     \resumeItem{Intern}
     {Worked as an intern at IRA OM Technologies on power systems - Smart Grid}
  \resumeSubHeadingListEnd

%-----------CERTIFICATES-----------%
\section{Certificates}
  \resumeSubHeadingListStart
    \resumeItem{Applications of IOT using Firebase}{\href{https://www.example.com/certificate-javascript}{\faIcon{link}}}
    \resumeItem{Software Engineering Usage in Product Development}{\href{https://www.example.com/certificate-html-css}{\faIcon{link}}}
  \resumeSubHeadingListEnd

%-------------------------------------------
\end{document}

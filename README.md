#First Project.
## 1. Installed tools

- Cursor IDE: An AI-powered code editor that makes assisted development easier.
- GitHub: Platform used for version control and repository storage.
- Codex: Extension used to assist in code generation and analysis within the editor.


## 2. steps completed

1. Creating a user account on GitHub.
2. Cursor IDE Editor Installation.
3. Initial editor setup.
4. Installing and activating the Codex plugin within Cursor.
5. Exploring the artificial intelligence tools available within the editor.
6. Synchronizing the Cursor editor with the GitHub account to enable version control..

## 3. Problems Encountered and Solutions

### 3.1 Installing the Claude Code add-on

-Problem: 
When trying to install the Claude Code plugin, it wasn't specifically available for the Cursor editor, as it only appeared as an extension for Visual Studio Code. Furthermore, the login option was not displayed.

-Solution: The documentation and internal workings of the Cursor editor were investigated, revealing that support for Claude is already integrated within the editor itself. 

Within the editor's chat, the automatic AI model selection option was disabled, and the various available options could be viewed, including:

- Claude Opus 4.6
- Claude Sonnet 4.6

This confirmed that Claude was already pre-installed on Cursor, so there was no need to install an additional extension.

### 3.2 Cursor synchronization with GitHub

-Problem: An issue occurred while trying to sync the Cursor editor with the GitHub account.

Solution: An information search was conducted to identify the correct authentication procedure. Subsequently, the authorization codes provided by GitHub were used, which allowed the synchronization between Cursor and the remote repository to be completed successfully.

## 4. Current Status

The development environment was correctly configured, allowing:

- Use Cursor IDE as the main editor.
- Access different AI models integrated within the editor.
- Synchronize projects with GitHub for version control.

------

# B2B YouTube Content Strategy Research

## Project Overview

This project analyzes how experienced marketers and founders use YouTube and professional platforms to share insights about B2B marketing, SaaS growth and product positioning.  

The goal of the research is to collect and organize content from industry practitioners who actively create educational content through YouTube videos, podcasts and LinkedIn posts.

The research focuses on professionals who **actively practice what they teach**, rather than only writing theoretical content.


## Tools Used

The following tools and platforms were used to complete this project:

- Cursor IDE for project development and repository organization
- GitHub for version control and project hosting
- YouTube for video content and expert insights
- The transcripts were obtained using the website: [https://downsub.com/]
- LinkedIn for collecting recent posts from selected experts
- AI coding assistants (Claude Code / Codex) to assist with research organization and file structuring


## Research Topic

The chosen research topic for this project is:

**YouTube Content Strategy for B2B Software**

This topic was selected because many SaaS founders, marketers and product strategists use YouTube to share educational content about marketing strategy, demand generation and product positioning.

## Experts Selected

Originally the project required identifying 10 experts. However, after reviewing several potential candidates, only 6 experts were included in the final research because they met the necessary project criteria (active content creation, relevant expertise and available public content).

The selected experts are:

1-Ali Schwanke
2-Alex Berman
3-Nathan Latka
4-Rand Fishkin
5-April Dunford
6-Dave Gerhardt

Some of the initially considered experts did not fully meet the project requirements, and due to time limitations additional candidates were not investigated further.

## LinkedIn Content Collection

For each expert, two of their most recent LinkedIn posts were collected and organized inside the repository.

The information was gathered using Claude Code or Codex through the AI features available in the Cursor IDE, which helped locate and compile the recent posts from each expert.

## All collected posts were saved in the following directory:

/research/linkedin-posts/

Each file contains the posts organized by author.

## YouTube Transcript Collection

The project also required collecting transcripts from YouTube videos created by the selected experts.

Due to technical limitations, the transcripts were not collected through the AI tools directly. Instead, a web transcript extraction method was used.

The transcripts were obtained using the website: [downsub.com]

This tool allows users to extract subtitles or transcripts from YouTube videos.

The transcripts were then reviewed and organized manually and saved inside the repository in the following directory:

/research/youtube-transcripts/

Each transcript file includes the video title, author, video URL and the transcript content.

## AI Tool Limitations

The original intention was to use Claude Code or Codex to retrieve YouTube transcripts through automated methods. However, this was not possible because the AI tools available in the Cursor environment required a Pro subscription to continue interacting with the AI chat.

Because of this limitation, the transcript extraction was completed using the alternative method described above.

Repository Structure

The project is organized using the following structure:

/research
   sources.md

   /linkedin-posts
      posts organized by expert

   /youtube-transcripts
      transcripts organized by video

This structure was designed to keep the research materials organized and easy to navigate.

## Conclusion

This project collected and organized content from several B2B marketing experts to better understand how professionals in the SaaS and marketing space share educational content online.

Despite some technical limitations and time constraints, the research successfully gathered relevant material from multiple credible industry experts and structured it in a clear and accessible format.


Made by Federico Ferrari.

---
layout: single
title: "Version Control and Git: A Guide for Non-Technical Users"
og_image: /assets/images/version-control-and-git.png
sequence: 2
excerpt: "Conceptual explainer covering version control and Git for non-technical users, without implementation details."
---

(in progress)

<div class="notice">
  <p><strong>Project Brief</strong></p>
  <ul>
    <li><strong>Audience:</strong> Non-technical users (spec work).</li>
    <li><strong>User Goal:</strong> To understand the big picture of version control and Git without getting lost in the technical details.</li>
    <li><strong>Problem:</strong> Version control and Git need to be explained, and Git can be intimidating for non-technical audiences.</li>
    <li><strong>Scope:</strong> This conceptual guide explains version control and Git without covering implementation details.</li>
    <li>
      <strong>Key Considerations:</strong>
      <ul>
        <li>Everyday examples such as emailing to yourself are used to help explain version control and Git for the intended audience.</li>
        <li>Implementation details such as CLI are omitted to avoid overwhelming the intended audience.</li>
        <li>The value of using Git is explained so that users can understand the practical significance of using Git in addition to understanding what it is.</li>
      </ul>
  </li>
    <li><strong>Success Criteria:</strong> The user can define commit, repository, branch, and merge, and explain the difference between Git and GitHub & GitLab.</li>
    <li><strong>Next Iteration:</strong> After evaluating user feedback, revise until 100% of pilot non-technical users meet the success criteria.</li>
  </ul>
</div>

## Sample

Version control is a way of managing different versions of the same project. If you keep making changes to a project over time, you want a way to track and manage these changes. Git has become the industry-standard way of accomplishing version control in the tech world. Understanding Git in more detail will help you appreciate the advantages of using Git in workflows such as docs-as-code (docs developed the same way as code).

## What is Version Control?
Suppose you want to create a Microsoft Word document. You may want to experiment with different headings, different fonts, and different layouts for graphics. In experimenting, you don't want to lose your prior progress. Consequently, you want a way to keep track of previous versions of the document so you can revert to previous versions if need be. This is where version control comes in.   

A simple form of version control would be emailing the document to yourself periodically. If you decide you want to revert to a previous version, you can simply download the previous version from your email. 

While emailing a document to yourself can work well for small personal projects, it is not realistic in collaborative environments. In collaborative environments where multiple individuals are working on the same project simultaneously, the different versions of the project will be out of sync with each other, and there is no easy way to reconcile them. 

This is where Git comes in. Git makes version control in collaborative environments practical. While Git is not the only form of version control, its advantages have made it the industry-standard form of version control in the tech world.    

## What is Git? 
Git is software that accomplishes version control. Git takes a snapshot of the entire project state at a given moment in time and records this snapshot. With these snapshots, Git has a history of the entire project state over time that can be used to revert to previous versions of the project. Each snapshot is called a **commit**. Users tell Git to take a snapshot by telling it to make a commit at specific moments such as finishing a section. Git stores commits in a **repository** or **repo** for short. A repository is like a photo album that stores a series of time-stamped photos of the entire project state allowing you to record changes over time. Once this photo album exists, it is easy to flip back to an earlier photo and start working from that point.   

Git does not have to be used in collaborative environments. However, Git is designed to make version control in collaborative environments practical. Using Git, you can set up a single main version of a project. Users can then make **branches** of the main version. These branches are a separate line of work that begin with the main version and then depart from it. Once the changes on these branches are deemed satisfactory, they can be **merged** into the main version of the project (called the main branch). Merging is when the changes on different branches are integrated into a single version. The end result is that the main version (the main branch) is updated to include the changes on the other branches. Team members in a collaborative environment can thus work independently of each other on their own branch, and once their work is deemed satisfactory, it can be merged into the main version.  After merging, branches can be deleted. GitHub/GitLab workflows also typically include a way for team members to request review and approval of their changes prior to merging them. 

**Note:** 
Git is not the same as **GitHub** and **GitLab**. Git is software that accomplishes version control, while GitHub and GitLab are websites that host Git repositories and facilitate collaboration. In a typical workflow, a team maintains the central repository for a project on GitHub/GitLab, and team members sync their work on their local machines to and from the central repository, subject to review and approval. Think of GitHub and GitLab as being like Google Drive.
{: .notice}

## Why Use Git? 
Git is not the only type of version control, but it has several key advantages: 

* Git **works quickly**. Git operates on a local computer, so there is no need to wait for data to be retrieved over the internet. In work environments, this translates to efficiency gains.
* Git **does not require an internet connection** to make commits. This means you can store snapshots while on an airplane or while the internet is down. In work environments, this translates to flexibility and resilience in the face of unexpected disruptions.   

    **Note:**
    While Git does not require an internet connection to make commits, in a typical workflow, an internet connection is ultimately required to sync local work with the central repository. However, a user can still continue local work without an internet connection temporarily.
    {: .notice}

* Git is **distributed**. Other forms of version control often synchronize different computers with a single location to store data without storing a full copy on the local computer. With Git, however, each computer using Git has a full local copy of the central repository. This means that if the central repository on a site like GitHub/GitLab is compromised, any computer that has an up-to-date sync with the central repository can be used as a backup. 
* Git **handles branching and merging well**. This means Git accomplishes more than just version control—it also makes version control in collaborative environments practical. While in some cases, Git cannot merge different branches and requires a human to intervene, even then, Git provides a way for humans to resolve the conflict. 

## Git in Action 
The following workflow scenario shows what collaborative version control with Git can look like. An outdoor adventure software company maintains an online help center for its consumer topo navigation app. A recent app software update requires updating the online how-to guide in three different areas. Technical writers working for the company each take on one of the areas to complete. The writers make a copy of the central Git repository on their local computers. They then make a branch to work on their assigned update independently. Once complete, the writers push their changes to the central repository for review. The documentation manager approves the changes, and the changes are incorporated into the how-to guide by merging the branches into the main branch. By merging the branches into the main branch, the company can easily incorporate the contributions of multiple technical writers working independently. This workflow results in better documentation for consumers and improved customer satisfaction.    

## Key Takeaways
* Git provides a way to keep track of changes to a project over time.
* The branching feature of Git allows for collaborative workflows—each team member can work independently on a separate branch, and these branches can then be merged with the main branch to incorporate each member's contributions. 
* Git has technical features that make it effective at its task—it is fast, it can be used offline (though a typical workflow ultimately requires internet), it is distributed, and it handles branching and merging well. 

## Glossary
* **Commit:** A snapshot of the entire project state at a specific moment in time.  
* **Repository (Repo):** The location where commits are stored (like a photo album with time-stamped photos).
* **Branch:** One of potentially many parallel versions of a project.  
* **Merge:** The process of integrating changes on different branches into a single version of the project.  
* **GitHub and GitLab:** Websites that host Git repositories (like Google Drive hosting a document) and facilitate collaboration.  

## Getting Started
* Git can be downloaded [here](https://git-scm.com/install/).
* The free [_Pro Git_](https://git-scm.com/book/en/v2) book by Scott Chacon and Ben Straub provides detailed instructions on how to use Git. 
* GitHub offers a [getting started guide](https://docs.github.com/en/get-started).
* GitLab offers a [getting started guide](https://university.gitlab.com/pages/getting-started).

{% include post_pagination.html %}

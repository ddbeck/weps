:WEP-Number: 0000
:Created: 2019-10-01
:Last-Modified: 2019-10-01
:Author:  - Eric Holscher
          - Sasha Romijn
          - Samuel Wright
          - Mikey Ariel
:Status: Draft
:Replaces: N/A
:Superceded-By: N/A

WEP0000 - Initial Launch of the WEP Process
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Abstract
========

This is the first Write the Docs Enhancement Proposal (WEP), which introduces the WEP process itself and proposes to implement it in the Write the Docs community. The WEP process enables anyone from the community to propose process and policy changes to the community. The community then reviews the proposed change and if the change is accepted, the policy or process change is implemented in the community. 

This "meta-WEP" follows the WEP process to show how the process works and to help the community learn how to use it.

Motivation
==========

When Write the Docs first started in 2013, it was a small collection of humans who were seeking a community of like-minded folks in Portland, Oregon. These folks named themselves **Documentarians**, and the community became our home to share knowledge and socialize with our peers from various roles, locations, and industries. 

Over the years, we have grown to a global community with multiple conferences, scores of meetups, and a robust Slack group with thousands of members. The conference teams converged and developed beyond anything that we imagined when we first started, and the Write the Docs organization has become just that -- an organization.

During the past year it has become apparent, by talking to various long-term community members and by reviewing our current processes and policies, that there is a need for a formal system to manage changes to the community. We have multiple platforms where community members can interact, and we want to provide a way to communicate and engage the global community in decisions that will affect how the community is organized and moderated.

We examined other open-source communities to see how they manage their governance and process changes, and we decided to propose the WEP system because we saw it was successful in multiple open-source communities, who contain a much larger user and contributor base and used similar systems for many years. We hope that laying the groundwork with this system will help Write the Docs scale globally with maximum transparency and collaboration.

We believe that the WEP process will help facilitate open decision-making by being a public place to change and document governance for the whole community. Having our foundational documents, and the conversations that lead to them, available publicly will inform new and existing members of the community. Over time, we hope that the WEP repository will become the foundational set of policies that the community is built upon, with this document being the first act.

Proposal
========

The WEP system consists of a dedicated `GitHub repository <https://github.com/writethedocs/weps>`_, which contains individual files that represent specific proposals to policies, processes, and programs in the community. The repository is public, and all WEPs are submitted and reviewed publicly by the entire community. 

What is a WEP?
--------------

WEP stands for Write the Docs Enhancement Proposal. A WEP is a document that provides process information to the Write the Docs community or that describes a new policy for the Write the Docs organization.

WEPs describe **policies and processes** surrounding Write the Docs events and online community, and therefore require community consensus. For example, a WEP might propose a change to an organizational process, community policies, or the decision-making process itself. 

Scope of WEPs
-------------

WEPs are generally intended for long-term policies that affect either a large number of community members, or that affect fewer but more significant segments of the community.

Examples of topics that should use the WEP process:

- Adjusting the structure of the Slack community to make it more accessible to new community members
- Policies about the structure of the Write the Docs organization
- Policy related to Slack team or channel guidelines
- Changes to the Code of Conduct (CoC)
- A grant policy to support conference attendees that need financial support
- A policy on how to balance various topics submitted to the Call for Proposals at the various Write the Docs conferences

Examples of topics that are out of the scope of the WEP process:
- Requests to change CFP policies in a specific conference
- Requests to create a new Slack channel
- Specific CoC violation reports
- Requests to create a new meetup

Topics that are out of scope for a WEP should be discussed in other community platforms, such as within the conference team, Slack team, or Code of Conduct team. The WEP team will direct out-of-scope pre-proposals to the relevant team in the rejection comments.

Generally, WEPs do not contain the names of individual people, but rather references to teams in the Write the Docs organization. Similarly, they don’t contain fixed budget numbers, but instead guidelines for how to implement the budget. 

How to submit a WEP
-------------------

Anyone from the community can submit a WEP! Here's how it works, and what to expect.

The WEP process and system are administered by the following teams:

Core Operations team
  There are several references in this WEP to the **core operations (CoreOps) team**. This team is currently known as the **core team** and the team description can be found on the `Core team page <https://www.writethedocs.org/team/#core-team>`_. The updated name is intended to reflect the purpose of the team more accurately in the context of its duties for the community. 

WEP team
  The **WEP team** is a new team that reviews WEP proposals for clarity and completeness. For the purpose of this WEP the team is initially composed of the Core Operations team, but in the the future will be open for other community members to join. 
  
Note that the process to join and leave teams is out of scope of this WEP and will be handled in a future WEP.

At a high level, the WEP submission process includes the following stages:

#. `Pre-proposal`_ — Someone has an idea and they start collecting early input and feedback to see if it is within the scope of a WEP. This can be done informally, publicly or privately.

#. `Draft submission and pre-review`_ — The WEP author writes a rough draft of the WEP and submits it in a pull request (PR) to the WEPs repository. The draft is pre-reviewed by an editor for style, formatting, and eligibility for the WEP process. If the WEP is pre-approved, it is accepted for discussion and the 30-day review period begins.

#. `Community review, discussion, and updates`_ — During the review period, the WEP draft is discussed, improved, and updated based on incoming feedback from the community. Feedback is welcome from the whole community, as long as it arrives within the review period. 

#. `Final review and resolution`_ — At the end of the review period, the WEP is examined for **lazy consensus**. A lazy consensus means a situation where the community either provided feedback, approved the WEP explicitly, or ignored the WEP altogether. In some cases where consensus wasn't reached, the review period might be extended, but never shortened.

#. `Implementation`_ — If the WEP is accepted, the processes or policies described in the WEP are implemented by the CoreOps team, the WEP author, or specific community members as defined in the WEP.

The following sections describe each stage in more detail.

Pre-proposal
............

The WEP process begins with an idea for Write the Docs. It is highly recommended that a single WEP contain a single key proposal or idea. 

If you have an idea for a WEP:

 - Discuss the idea in a public forum such as the Write the Docs Slack.
 - Gather initial community feedback to enhance your WEP. 
 - Make sure your idea applies to the entire community and not just yourself.

A WEP can be co-authored by more than one community member, but we recommend keeping the number of co-authors small and choosing a representative who will submit the PR to the WEPs repository on behalf of the co-authors.

Draft submission and pre-review
...............................

A draft WEP must be submitted in a GitHub pull request to the `writethedocs/weps <https://github.com/writethedocs/weps>`_ repository, in the ``drafts/`` directory. If you need help with working with GitHub or creating a PR, please feel free to send an e-mail to support@writethedocs.org, and the Write the Docs team will help you get started.

The WEP draft must follow these guidelines:

- The WEP's proposed change must be specific and the resulting action clear.
- The WEP fits the scope of the WEP process, as described in **Scope of WEPs**. WEPs that are out of scope of the process will be rejected by the WEP team.
- Content format must follow the WEP style as described in the **WEP format and style** section. This includes language, grammar, structure, and markup. The PR might be blocked until proper formatting rules are applied.
- The WEP content is complete. If you want to submit a Work in Progress (WIP) draft before it is ready for pre-review, you can mark the PR as ``WIP`` and the review team will wait until the draft is ready.
- **Allow edits from maintainers** option is selected. This helps the reviewer merge your WEP draft if it is accepted.
- The PR is tagged with a **draft** label in GitHub, to indicate that it is in a draft state and is ready for pre-review. 

After the pull request for the WEP draft is submitted, a WEP team member reviews the pull request to make sure it adheres to the guidelines. If the WEP is clearly not ready, the reviewer might reject the pull request and ask the author to submit a new WEP after the problems have been fixed.

The WEP team reviewer does not vote on the proposed change itself, and only reviews the WEP for scope compliance, format, and completeness. The pre-review period is usually one week, but might change based on the scope of the pre-review feedback and the availability of the author to implement changes.

After the WEP is ready for the community review, the reviewer assigns the **ready-for-discussion** label to the PR. The CoreOps team is then responsible for distributing announcements of each WEP to the relevant community segment. For example, a WEP about meetups will be shared with the Meetup team for distribution between the meetup organizers. For some WEPs, community-wide announcements will be made on Slack or to the mailing list. 
  
Community review, discussion, and updates
.........................................

The standard community review period for a WEP is **30 days**. The WEP is decided on by a process called **lazy consensus**. This means that community members either provide feedback, approve the WEP explicitly, or ignore the WEP. 

If the review period ends without a clear consensus, but further discussion is still needed, the review period might be extended by the WEP team. The review period is never shorter than one month, but other WEPs can be submitted in the meantime, and multiple WEPs might be undergoing a community review simultaneously. 

During the community review period, the WEP goes through one or more iterations of feedback and updates. Community feedback is submitted in the form of comments to the PR, and the WEP author is responsible to update the WEP content in case the incoming feedback is accepted.

All discussion on the WEP must happen on the PR in the form of comments in order to be considered as official feedback on the WEP. Of course external conversations can happen on other platforms, but the official record for a WEP discussion is only on the PR itself. If discussion happens on another platform, we recommend copying the most important points or the results of those discussions into the WEP comments.

You must have a GitHub account to post comments to a PR. If you need help getting started with GitHub, email support@writethedocs.org and the WTD team will help you set up your account and get familiar with GitHub basics. 

Final review and resolution
...........................

At the end of the community review period, the WEP is accepted if it meets the minimum criteria and received lazy consensus as described in the previous process stages.

The WEP team reviews the final WEP content and if it is accepted, the team merges the PR, removes the **ready-for-discussion** flag, and moves the WEP to the ``accepted`` directory of the GitHub repository. 

Possible resolutions for a WEP are:

Accepted
  Reason: Community feedback was completed with lazy consensus achieved, and the WEP content is complete and follows the formatting guidelines. 
  Action: The WEP team merges the PR and stores the WEP in the ``accepted`` directory.

Rejected
  Reason: Community feedback led to disagreements about the WEP that cannot be resolved, or the original goal of the WEP is no longer considered an improvement to the community. 
  Action: The WEP team moves the WEP to the ``rejected`` directory and merges the PR with a description of the rejection decision.

Withdrawn
  WEP author is no longer interested in pursuing the change, or no progress was made during the pre-review stage before the WEP was sent to community review. 
  Action: The WEP author moves the WEP moves the WEP to the ``withdrawn`` folder and merges the PR with a description of the withdrawal decision.

If no community consensus was reached, the CoreOps team has the final authority to decide the resolution for a WEP. The CoreOps team is responsible to communicate their decision in the PR discussion and in community announcements as needed.

Any community member can restart the WEP process on a rejected or withdrawn WEP in the future, by creating a new PR and updating the WEP according to the new information or ideas. If you are interested in restarting a WEP that was authored by someone else, we encourage you to contact the original author before you begin, in case they are interested in collaborating or have information that can help you in the process. 

Implementation
..............

After a WEP is accepted, the work outlined in the WEP must be done. For most WEPs, the CoreOps team is responsible to take the needed action or coordinate with other teams to take the need actions.

For example, if this WEP is accepted, it means the system is now in place and the CoreOps team will publish the information to the community website and establish the WEP team, along with other related tasks that need to be done to implement the process in the community. 

Some WEPs might require specific community segments to implement the resolution, and such requirements are described in the WEPs directly. 

WEP format and style
--------------------

To make the authoring and reviewing process easier, WEPs must follow a common format and style. 

We use `reStructuredText <http://docutils.sourceforge.net/rst.html>`_ markup language for all WEPs, to align with the same markup that is used in all other Write the Doc documentation.

In most cases, you can start by copying the `WEP template <../wep-template.rst>`_ and adding content as needed. The following sections describe the various sections of the template:


File name
.........
The file name must follow the naming convention ``WEP[####]_[descriptive-but-short-title]``. For example, this WEP file is named ``WEP0000_wep-proposal``. In another example, a WEP to propose a new Slack channel naming convention might be named ``WEP0001_slack-channel-renaming``.
  
Metadata
........
The WEP file must begin with a header list of metadata fields, using the standard `RST field list <http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html#field-lists>`_ format.

The field list usually includes the following fields:

- ``:WEP-Number:`` - Number of the WEP, in running order in 4-digit format. Only use the number value, without the acronym **WEP**. For example, this WEP is numbered ``0000``. If the number is unknown or unassigned when you first create the WEP, you can leave this field blank and the number will be updated at the resolution stage.
- ``:Created:`` Date of initial creation, in the format YYYY-MM-DD. 
- ``:Last-Modified:`` Date of the most recent changes to the WEP, in the format YYYY-MM-DD. 
- ``:Author:`` - Full names of one or more authors of the WEP. Do not write email addresses or social media nicknames in this field. If the WEP is co-authored by multiple people, use a bulleted list similar to the header of this WEP.
- ``:Status:`` - Current status of the WEP. All WEPs begin with a ``Draft`` status, and the field changes with every stage in the WEP lifecycle. For example, ``Accepted``, ``Rejected``, ``Withdrawn``, ``Final``, or ``Superseded``.
- ``:Replaces:`` - Optional. If this WEP was created instead of a previous WEP that was rejected or withdrawn, list the number and title of the previous WEP.
- ``:Superceded-By:`` - Optional. If this WEP is rejected or withdrawn and a newer WEP was submitted instead with updated content, list the number and title of the WEP that supercedes this WEP.

Structure
.........

Each WEP must contain the following sections:

#. **Header.** Header with a list of metadata fields as described in this section.
#. **Title.** Short descriptive title of the WEP. The title must follow the naming convention ``WEP[#] - [Descriptive title]``.
#. **Abstract.** Short description of the topic that the WEP addresses. Use only 1-2 paragraphs and focus on the summary of the topic.
#. **Motivation.** Background information explaining why the existing processes or solutions need to change.
#. **Proposal.** Full description of the proposed change. This section can be as short or as long as needed, including explanations or alternatives if applicable. Use sub-headings to divide the proposal section if it contains a large amount of text.
#. **Copyright.** Boilerplate license statement for the WEP. All WEPs must be published under the **Creative Commons CC-BY 4.0** license. This boilerplate text must be used as-is without alterations.

If you are unsure whether the WEP you are authoring is structured correctly, you can submit it as a WIP draft and ask for help from the WEP team, or email us at support@writethedocs.org and we will be happy to help you with the preparation.

Acknowledgments
---------------

The WEP process is based on the `Django DEP <https://github.com/django/deps/blob/master/final/0001-dep-process.rst>`_ process, which in turn was based on the `Python PEP <https://www.python.org/dev/peps/pep-0001/>`_ process. We would like to thank the Python and Django communities for providing these open-source resources publicly and freely to help other communities.

Copyright
=========

This document is published under the `Creative Commons CC-BY 4.0 Attribution <https://creativecommons.org/licenses/by/4.0/>`_ license.

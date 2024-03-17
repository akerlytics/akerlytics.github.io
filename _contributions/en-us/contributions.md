---
page_id: contributions
layout: about
title: contributions
permalink: /contributions/
nav: true
---

The simplest contribution to the document makes use of email templates. If a section of a document doen't fit your view, or if you whant to make changes, search for this link `contribute`.

Contributor's section is a brief explanation on how to use the email template. A section for email `title` and `body` needs to be copied to your email providor interface. 

Note on adding editing comments for a section: since a section can get support via the `show_support` functionality. Minor changes will most likely appear in a foldable region of the section at the end, next to the *giscus* comments. 


## Email Templates

Here is an example of an Email template:

```markdown
# Example email template

# Intent of contribution
- [ ] this is an unselected option example.
- [x] this is a selected option example.

show_support:
  - [ ] I strongly support this section.
  - [ ] I support this section.
  - [ ] I am indiferent to this section.
  - [ ] I don't support this section.
  - [ ] I strongly disagree with this section.
  
suggestions:
  comment_scope: 
    - [ ] public comment (if empty, email will be queued for manual review by an editor)
  
  comment_type:
    - [ ] Information structure related detail
    - [ ] Language related detail
    - [ ] Legal query.
    - [ ] Presentation suggestion/observation/request

follow-up:
  modifications:
    - [ ] send me an email on the first time this section gets changed
    - [ ] send me an email on all changes for this section 

    
<<!-- original-section -->
## this is an example type 2 header

This sections needs language correction.

<<!-- end original-section --> 

<<!-- modified-section -->
## this is an example type 2 header

This section needs language correction.
<<!-- end modified-section --> 
```

Emails will be collected and attributed a unique identifier. Spam emails will be ignored. Emails can be verified per voter region of their democratic system.

if a section where you have submitted a support weight changes, the support for past version will be kept and an automatic email will be sent to update support status.
  

### Subscriptions

A section for each email template is designated for unsubscription of email.

```markdown

past-contributions:
  - [ ] request history
  - [ ] remove support for:
    - [ ] this section: /political_issue_tracker/CAN/who
    - [ ] specify section via path here: /political_issue_tracker/CAN/who/.....
    - [ ] this political issue
    - [ ] all political issues

  - [ ] unsubscribe from automatically sent emails:
    - [ ] errase my support data
```

### Email Attachments

```markdown
attachments:
  - [ ] This email contains an image attachment used in the current text change submission.
```
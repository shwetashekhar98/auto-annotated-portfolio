---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: inset
    title: >-
      i AM A Master’s student pursuing Computer Science AT NYU,Former Software
      Developer AT GEP Worldwide
    subtitle: ''
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: center
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: "````\n<html lang=\"en\">\n<head>\n    <meta charset=\"UTF-8\">\n    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">\n    <title>Shweta Shekhar - Passionate Technologist</title>\n    <style>\n        body {\n            font-family: Arial, sans-serif;\n            background-color: #f4f4f4;\n            margin: 0;\n            padding: 0;\n            display: flex;\n            justify-content: center;\n            align-items: center;\n            height: 100vh;\n        }\n        .container {\n            background-color: white;\n            padding: 20px;\n            border-radius: 10px;\n            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);\n            max-width: 600px;\n            text-align: center;\n        }\n        h1 {\n            color: #2c3e50;\n        }\n        p {\n            color: #34495e;\n            line-height: 1.6;\n        }\n        .emoji {\n            font-size: 1.2em;\n        }\n        .highlight {\n            font-weight: bold;\n            color: #e74c3c;\n        }\n        .connect {\n            margin-top: 20px;\n            background-color: #3498db;\n            color: white;\n            padding: 10px 20px;\n            border-radius: 5px;\n            text-decoration: none;\n        }\n        .connect:hover {\n            background-color: #2980b9;\n        }\n    </style>\n</head>\n<body>\n```\n````\n\n```\n<div class=\"container\">\n    <h1>\U0001F469‍\U0001F4BB Hi, I’m Shweta—A Passionate Technologist!</h1>\n    <p>\n        Before diving into the world of academia \U0001F331, I spent four years as a <span class=\"highlight\">Software Engineer at GEP Worldwide</span> \U0001F3E2, where I designed scalable solutions and optimized cloud-based platforms. My journey has been driven by <span class=\"highlight\">innovation</span> \U0001F4A1, <span class=\"highlight\">problem-solving</span> \U0001F6E0️, and a deep curiosity for <span class=\"highlight\">cutting-edge technologies</span> \U0001F916.\n    </p>\n    <p>\n        <strong>What I love:</strong>\n    </p>\n    <ul class=\"emoji\">\n        <li>\U0001F310 Building robust APIs that power modern applications</li>\n        <li>\U0001F9E0 Streamlining operations with machine learning models</li>\n        <li>\U0001F680 Exploring the latest JavaScript frameworks</li>\n    </ul>\n    <p>\n        At <span class=\"highlight\">NYU</span> \U0001F3D9️, I’m refining my expertise in <span class=\"highlight\">data science</span> \U0001F4CA, <span class=\"highlight\">machine learning</span> \U0001F9D1‍\U0001F4BB, and <span class=\"highlight\">full-stack development</span>. My goal? To <span class=\"highlight\">redefine how technology shapes our future</span>! \U0001F30D\n    </p>\n    <p>\n        When I’m not coding \U0001F4BB, you can find me:\n    </p>\n    <ul class=\"emoji\">\n        <li>☁️\U0001F916 Exploring the latest in AI and cloud technologies</li>\n        <li>\U0001F3C6 Participating in hackathons, where I bring innovative ideas to life</li>\n    </ul>\n    <a class=\"connect\" href=\"https://www.linkedin.com/in/shweta-shekhar\">Let’s connect and explore how technology can push boundaries together! \U0001F91D✨</a>\n</div>\n```\n\n"
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Experience
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---

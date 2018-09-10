# How to make the web accessible

Before we go into approaches for making an accessible website, it is important to understand the basic pieces needed for anyone to access a website.

| Component | Description | Examples |
| :--- | :--- | :--- |
| **Web Content** | The informational content put on a website. | text, images, forms, multimedia \(audio, video, animation\), any markup code, scripts, applications |
| **Authoring Tools** | The tools to build a website. | code editors, document conversion tools, content management systems \(CMS\), blogs, database scripts |
| **User Agents** | The software people use to access web content. | desktop graphical browsers, voice browsers, mobile phone browsers, multimedia players, plug-ins , assistive technologies |

To be able to access a website, these components need to play well together. If web content is not available, you wouldn't see anything on the website. If authoring tools are not available, you couldn't have your information or messages on your website. If user agents are not available, you cannot get to the website or the content on the website. Every component is equally important to make a website available.

Web accessibility principles and techniques support these components, permitting websites to be available to broad range of users.

{% hint style="info" %}
Learn more about [how people with disabilities use the web](global-obstacles.md).
{% endhint %}

## Think POUR

WCAG lays out four guiding principles that are important for creating an accessible web experience called POUR \(Perceivable, Operable, Understandable and Robust\). By following these guidelines from the design through to the implementation stages, Mayflower strives to provide an intuitive and fully accessible user experience.

### Perceivable

Starting at the most basic level, users must be able to process information. The information could be text, audio, static image, video, and so on, things presented in your website, which are referred as **web content**.

**Ask yourself**: Is there anything on our website that a blind, deaf, low vision, or color blind user would not be able to perceive?

### Operable

Overall, users can easily navigate, find content, and determine where they are. In particular users using alternatives like keyboard-based operations should be able to navigate and understand the content of your website.

**Ask yourself**: Can all functions of our website be performed with a keyboard? Can users control interactive elements of our website? Does our website make completing tasks easy?

### Understandable

If users can perceive and operate a website, that doesn't mean they can understand it. Understandable websites use clear, concise language and offer functionality that is easy to comprehend. Writing should be clear and concise.

**Ask yourself**: Is all of the text on our website clearly written? Are all of the interactions easy to understand?

### Robust

Robust content is compatible with different browsers, assistive technologies, and other user agents. One of the best ways to meet the principle of robustness is to follow development standards and conventions. Clean code is generally more robust and consumable across platforms.

**Ask yourself**: Does our website only support the newest browsers or operating systems? Is our website developed with best practices?

## Making the web accessible 

**Structured presentation**

Pages need to be marked up in a reading order that makes sense. The flow of page elements such as headers, footers, navigation,  and the main content area are key to a screen readers understanding of the page.

**Semantic content**

Screen readers process the content as it's marked up. If the content doesn't have semantic markup, a screen reader may not pass on its context, making it harder for users to understand. Screen readers recognize headings, links, lists, forms, and so on, and announce what those elements are before reading through their contents. Organize information to have with meaning \(semantic structure\). Design with text and create information hierarchies. When the presentation is disabled, the web content should still be able to communicate its message effectively.

Users should be able to bypass extraneous or irrelevant pieces of content in order to focus on the content of interest to them. They should be able discern the structure of the content by its headings, subsections, bulleted lists, and other elements of semantic markup.

Well organized content helps users to orient themselves and to navigate effectively. Such content includes:

* Pages have clear titles and are organized using descriptive section headings;
* There is more than one way to find relevant pages within a set of web pages;

  Users are informed about their current location within a set of related pages;

* There are ways to bypass blocks of content that are repeated on multiple pages;
* The keyboard focus is visible, and the focus order follows a meaningful sequence;
* The purpose of a link is evident, ideally even when the link is viewed on its own.

**Non-text content needs alternative presentation**

This means providing text for those who cannot hear, and audio for those who cannot see. For non-text content such as images, movies,  and videos, screen readers need to have access to alternative text presentation in order to accurately convey this content to users. Audio content should include captions or transcripts. Sign language can also supplement information and text that is challenging to read. 

Text alternatives convey the purpose of an image or function to provide an equivalent user experience. For examples:

* Short equivalents for images, including icons, buttons, and graphics;
* Description of data represented on charts, diagrams, and illustrations;
* Brief descriptions of non-text content such as audio and video files;
* Labels for form controls, input, and other user interface components.

**Keyboard accessibility**

Screen reader users use the keyboard as their primary means of navigating the web. All functionality that is available by mouse should be available to the keyboard. Double check that keyboard focus does not get trapped in any part of the content. 

**Users can easily navigate, find content, and determine where they are**

With web pages or sections of Web content, users should be able to bypass extraneous or irrelevant pieces of content in order to focus on the content of interest to them. They should be able discern the structure of the content by its headings, subsections, bulleted lists, and other elements of semantic markup.

Well organized content helps users to orient themselves and to navigate effectively. Such content includes:

* Pages have clear titles and are organized using descriptive section headings;
* There is more than one way to find relevant pages within a set of web pages;

  Users are informed about their current location within a set of related pages;

* There are ways to bypass blocks of content that are repeated on multiple pages;
* The keyboard focus is visible, and the focus order follows a meaningful sequence;
* The purpose of a link is evident, ideally even when the link is viewed on its own.

**Text presented in graphics**

Some kinds of content are difficult to interpret when enlarged. For example, graphics that contain text can become blocky and pixilated, making the text difficult to understand. Text should be resizable up to 200% without losing information, using a standard browser

**Horizontal scrolling**

For users leveraging screen magnifiers, websites with horizontal scrollbars are difficult to use.

**Consider color contrast**

Make sure your default foreground and background color combinations provide sufficient contrast.

**Alternative presentation of colors**

Color should not be used as the only way of conveying information or identifying content. If a color and only the color conveys important information, provide an alternative way of obtaining this information or change the graphic. 

**Control options for media players**

Media players need to provide options to display captions and change caption colors, control volume and adjust text sizes.

**Providing sufficient time to complete a task**

Some people need more time than others to read and use the content. For instance, some people require more time to type text, understand instructions, operate controls, or to otherwise complete tasks on a website. Make sure users are given enough time to complete tasks, such as to fill out online forms. 

Examples of providing enough time include providing mechanisms to:

* Stop, extend, or adjust time limits, except where necessary;
* Pause, stop, or hide moving, blinking, or scrolling content;
* Postpone or suppress interruptions, except where necessary;
* Re-authenticate when a session expires without losing data.
* Time limits for completing an action should be generous or configurable.

**Good presentation**

It is important to include both visual and non-visual orientation cues, page structure, and other navigational aids. Inconsistent, unpredictable, and overly complicated navigation mechanisms and page functions provider a poor user experience for all users.

Many people rely on predictable user interfaces and are disoriented or distracted by inconsistent appearance or behavior. Examples of making content more predictable include:

* Navigation mechanisms that are repeated on multiple pages appear in the same place each time;
* User interface components that are repeated on web pages have the same labels each time;
* Forms should follow a logical flow and provide clear labels.
* If a user takes an action, the connection between the action and the result should be obvious.
* Significant changes on a web page do not happen without the consent of the user.

**Do no assume the user will remember**

Some users may have memory difficulties that impair their ability to remember how they got to content. Any kind of reminder of the overall context of a web site can help people with memory deficits.

**Provide clear instructions and a predictable flow**

Some individuals have a difficult time solving problems as they arise. In many instances, their resilience can be low and the resulting frustration is such that they choose to leave the site and not persist to solve the problem. Providing instructions at the start of a task will eliminate or at least reduce the overall number of user errors. Error messages should be as explanatory as possible, telling users what they did wrong and how to fix the problem. Also, avoid extreme changes in the context of the web site without first warning users. All functionality should be as predictable as possible, and any deviations from predictability should be preceded by warnings and/or explained to users after the changes occur.

Sites and apps should be forgiving. All people, not just those with disabilities, make mistakes through forms and other interaction, which can be confusing or difficult to use. Examples of helping users to avoid and correct mistakes include:

* Descriptive instructions, warnings, error messages, and suggestions for correction;
* Context-sensitive help for more complex functionality and interaction;
* Opportunity to review, correct, reverse submissions, or cancellation options if necessary.

**Consider attention limitations**

There are many individuals that have difficulty with focusing their attention to the task at hand. Distractions such as scrolling text, blinking icons and pop-up windows can make the web environment difficult or even impossible. Avoiding anything that draws a person's attention away from the main content and using good design, such as color, white space, and simple presentation can help users focus on important content and functionality.

**Consider reading, linguistic, and verbal comprehension**

Some individuals have difficulties understanding text in various severities. It is important for content authors to write as simply and clearly as is feasible, taking into account the primary audience - including those who may have difficulty with some of the content. Avoid using non-literal text such as sarcasm or colloquialisms as these can be challenging to understand. The unstated assumptions and implied meaning of written content may seem obvious to the writer, but readers may not have the necessary background knowledge. Some readers may not have the skills to infer meaning from text without additional help.

* Identifying the primary language of a web page, such as Arabic, Dutch, or Korean;
* Identifying the language of text passages, phrases, or other parts of a web page;
* Providing definitions for any unusual words, phrases, idioms, and abbreviations;
* Using the clearest and simplest language possible, or providing simplified versions.

**Consider math comprehension**

Mathematical expressions are not easy for everybody to understand. Often it is helpful to explain math conceptually, either with or without the formulas. Conceptual explanations help readers understand the reasoning behind the math.

**Consider visual comprehension**

Some individuals have difficulties processing visual information, the opposite of the problem experienced by people with reading and verbal processing difficulties. For example, they may not realize that a photograph of a person is a representation of a person, though they can plainly see the photograph itself \(as an object\) on the web page. For these people, a moving, talking person in a video may be easier to mentally process than a static image of a person in a photograph. Video and multimedia, accompanied with narration, may be the best way to communicate to these individuals.

#### Be weary of visual effects

Some people are susceptible to seizures caused by strobing, flickering, or flashing effects. Make every effort to ensure that your content does not have strobing, flickering, or flashing effects. Even if an animating or moving object does not cause a seizure, it may cause nausea or dizziness in some people. For these user avoid high contrast graphics with tight parallel lines; animated scrolling that lasts longer than perhaps 1/4 second; parallax or reverse parallax scrolling, and moving images beneath static text.

  



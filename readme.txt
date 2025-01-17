=== QuizU Branched ===

**Contributors:** jbent124
**Tags:** quiz, questionaire, poll, branched, chained,
**Requires at least:** 3.3
**Tested up to:** 4.8.1
**Stable tag:** 1.0

A multi-purpose and flexible quizzes / questionaires / polls plugin with integrated "Branched" or "Chained" logic.


== Description ==

Craft flexible quizzes composed of single, multiple, and open answers, with optional "branched" or "chained" logic. With QuizU, you have the ability to guide your users trough different combinations of inter-connected questions that lead to different results, or calculations based on their accumulated score.

Branches (paths), coupled with different question types, provide QuizU with great flexibility, making it suitable for many kinds of quizzes, tests and questionaires.


== Special Features ==

* **Shortcodes, widgets and global quizzes**

QuizU's widget rests in your sidebar and shows up when it detects a quiz linked to the current post. Aditionally, every quiz has its own shortcode to copy and paste into the content of any page or post.

If you want a more global solution, you can also select a quiz to be displayed in all posts or pages.


* **Link each answer to a different question or result**

Each answer can be linked to a question of your choice, to a specific result, or to the calculation of the final scores. If no answer is linked, the next question in the same branch, or in the next one will be selected. If QuizU does not find a next answer, and the current answer is not liknked to a result, the first result created will be displayed.


* **Single choice, multiple choice, and essay-type questions**.

Decide the score or path that each answer will lead to for all question types. You can create an unlimited set of correct or incorrect answers for essay-type questions.


* **Score based results**

Assign positive or negative scores for each answer. The sum of all scores at the end will determine the correct result according to the total score, or the highest scoring option (ie. A, B, C, D, etc).


* **Control the words displayed**.

Customize the phrases your users will see while progressing through your quiz.


* **Color code your branches**

Choose a default color to theme your quizzes, and specific colors for each branch.


* **Manage permissions**

Choose who can edit, and who can take your quizzes.


* **Social networks and email sharing**.

Let your users share your quizzes through their preferred channels. Supports e-mail, Facebook, Google +, Twitter and Whatsapp.


* **Thumbnail hint for each option**.

Setup a “hint” image to be displayed next to each option.


* **Drag & drop question sorting**

Reorder questions by clicking and holding the “X” icon at their top right corner.


* **Real time editing and autosave (optional)**

No page reloading. No information loss. You can choose to save every change instantly, or to save everything at the end with a single click.


* **Quiz preview**.

Experience your quiz the way your users would; before publishing it. If autosave has been disabled, you will need to save your quiz before previewing it.


== Installation ==

1. Upload the .zip file via the "add new plugin" interface
2. Activate the plugin
3. Create and preview / publish a few quizzes
4. Link a quiz to a post or page, or make it global for all posts / pages


== Getting Started ==

After installing, QuizU will add a new menu in your WP admin sidebar. QuizU’s menu contains a link to a list with all your quizzes, a direct link for creating new quizzes, and a link to QuizU’s settings page.

Shortcodes are displayed in the quiz list page. In the quiz edit / creation page you can determine whether to display the current quiz for all users, or only for logged in users; as well as the criteria used to calculate results.

Once you have created your quiz you can go to the edit screen of the post or page where you want it displayed and select it, or you can paste its shortcode into the post’s content.


== Results Criteria ==

You may choose to have the final scores listed for your users once they complete a quiz, and you may also decide if results are determined by “branch”, by “total score”, or by the “highest scoring option”. For the last two, you will need to determine each result’s score range or triggering option.


* **Branched**

You determine exactly which question will lead to which result.

* **Total Score**

Results are displayed according to the sum of the final scores awarded to the user.

* **Highest scoring option**

The score of each “option index” (ie. A, B, C, D, etc) is summed separately, and the winning "index" is calculated.


== Types of Questions ==

Each of the questions’ answers may award a positive or negative score. Essay-type questions will only count if answered correctly. Single choice is the default type, while multiple choice or essay-type questions are enabled with a click.


* **Single Choice**

The chosen answer will determine the “branch” the user will follow.

* **Multiple Choice**

The scores of all chosen answers will be summed with the total. Only the linked question or result of the first option will be used. 

* **Essay-Type**

Open answers with an infinite number of possible correct (or penalty) answers. The score of the typed answer will only be summed if it matches an item in the set of answers. This type of question has two types of link. The "main" one, for the question itself, and another one for each answer. If no matching answer is provided or the matched answer is not linked, the main link will be used.


== Frequently Asked Questions ==

Please use the forum.


== Screenshots ==

1. Main view
2. Questions view
3. Results view
4. Single Choice / Multiple Choice
5. Open Answer
6. Results
7. Activate Widget for Post/Page
8. Settings page


== Changelog ==

= 1.0 =

* First stable version

= 1.1.0 =

* Important bugs fixed. User experience and admin design improved.


== Upgrade Notice ==

= 1.0 =

* This is the first stable version

= 1.1.0 =

* Important bugs corrected. Upgrade your plugin version to avoid conflicts/loss of data. Admin Panel's speed and styles have also improved.


== Translations ==

* Spanish


== Credits ==

Thanks to:

* WordPress
* jQuery
* JsSocials
* FontAwesome
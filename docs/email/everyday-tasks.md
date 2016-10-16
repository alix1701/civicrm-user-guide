Les tâches quotidiennes
==============

Ce chapitre décrit les tâches quotidiennes liées à la gestion de vos envois de courriels de masse. L’envoi en masse est expliqué dans le chapitre [Mass mailings using CiviMail](../email/mass-mailings-using-civimail)

Envoi d’un courriel à une seule personne (avec CC et CCI)
-----------------------------------------------
Vous pouvez utiliser CiviCRM pour envoyer des courriels individuels. Une telle utilisation peut s’avérer utile si vous souhaitez que d’autres personnes de votre organisation soient en copie ou, alors, si vous voulez réutiliser un modèle de courriel précédemment défini.

1.  Recherchez la personne destinataire du courriel. Il y a deux façons de procéder :
    -   Utiliser la zone de recherche rapide (en haut à gauche). Cliquer à l’intérieur et saisissez les premiers caractères du nom ou de l’adresse email de la personne.
        Dans la liste de choix contextuelle, sélectionnez la bonne personne.
    -   Sélectionnez l’option de menu **Recherche > Chercher un contact**. Saisissez le nom de la personne ou son adresse email. Cliquer sur le bouton Chercher, puis sur le nom de cette personne lorsque le résultat de la recherche apparait.

2.  From the contact summary page, click **Actions > Send an email** or
    click the **Activities** tab and choose **Send an Email** from the
    dropdown menu.
3.  You can add additional recipients using the CC and BCC fields.
4.  If you have templates defined, you can choose one from the Use
    Template dropdown menu. Selecting a template populates the text
    content and HTML content fields with the message content from the
    particular template you have chosen. You can then edit that
    content.
5.  Enter your content or add content to your template. If you just wish
    to send a Plain Text version of your email, ignore the HTML Format
    section and click on the Plain Text Format section. Enter your
    message in the box.
6.  Click **Send** to send your message.

To see the activity that was just recorded of the email sent, click the
Activities tab of the contact.

Sending a quick email to less than 50 contacts
----------------------------------------------

In the results from a search, CiviCRM makes "Send Email to Contacts"
available from the actions dropdown menu. This allows you to send an
email to more than one contact at a time. Sending an email this way is
relatively quick, but it provides no options for tracking email and
doesn't give contacts the option to opt out. It is bad practice to use
this method for mass mailings, which is why it is limited to 50
contacts. For mass mailings, use CiviMail.

1.  Click **Search > Find Contacts** (or **Advanced
    Search**). Choose your search criteria and click Search (or use
    any other search to find the contacts that you wish to email).
2.  From the search results screen, choose some or all of the contacts
    and click **Actions > Email -send now (to 50 or less)**.
3.  Follow the same steps as in sending an email to one person.

Each of the recipient contacts will have this email recorded as an
Activity in their record. An activity will also be recorded for the
sender. The activity record will also list all the other message
recipients. Unlike with mass mailing (see below) there is no one place
where all emails sent via the Send Email function are listed.

**Note:** If a message is sent to multiple recipients, each recipient
will see only their own email address in the To field. Because the
recipients don't see who else received the email, you might want to
mention whom you are sending it to in the text of your mail (for
instance: "TO: Members of the board, staff")

Inserting an image in an email
------------------------------

Click the **image button** in the WYSIWYG editor.

![](../img/Screen%20Shot%202015-04-25%20at%203.06.40%20PM.png)

The Image Properties window will appear. Click **Browse Server** to look
for image files on your server.

![](../img/civimail_window%20to%20browse%20server%202.jpg)
In the left sidebar, you will see a directory of files. If the image you
need is already uploaded to your server, navigate to it in the directory
and select it. If not, Click **Upload** to choose a file from your
computer.

![](../img/civimail_file%20directory%203.jpg)

Your computer's file-browsing window will open. Find the image file you
want,
click to select it and click **Open**. You can repeat this process to
upload multiple files to CiviCRM at once.

To insert, double click on the image you want. You'll return to the
Image Properties window of your email.

Here you can add adjust the size and alignment of the image and the
border around it. You can also fill in the Alternative Text field, which
is text that appears when the image is not available to the reader (if
they choose not to load images in their email client, or are using
a[](http://en.wikipedia.org/wiki/Screen_reader "Screen reader") screen
reader due to a visual impairment). The alternative text ensures no
information is lost; it's a best practice to always include alt text for
images to make email accessible to all user communities.

Click **OK** to insert the image.

![](../img/civimail_Insert%20image%206.jpg)

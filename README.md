# Goodstuff.fm

## Logging in

### Visit https://manage.siteleaf.com/login
You'll be provided a Siteleaf account to add episodes, manage your show, and add posts to the site.

### Select **Goodstuff** from **My sites**
If you have an existing Siteleaf account, you will see other sites you can manage here. For our purposes, you'll select Goodstuff from the list.

## Your Show

### Viewing Episodes
You'll land on the **Pages** screen: a list of all of the pages on Goodstuff.

To manage your show and view episodes, you'll select the Collection with your show's name on the left (ex. 3G3Q). Here, you'll see a list of Documents, or Episodes, and Collection Settings.

If you'd like to access and manage your show more directly, you can bookmark the collection/show's URL in Siteleaf.

***

### Creating an Episode
To create a new episode, you'll click on **New document** on the top right of your show's collection.

You can also bookmark this page if you'd like to go directly to creating a new episode.

Once you have finished editing your episode, you must press the green **Save** button. This does not publish the episode. You will need to then press the **Publish Changes** button on the top right to publish your episode.

***

### New Documents

![Title](https://cl.ly/2Z3R1j3h1T1l/Screen%20Shot%202017-02-12%20at%201.22.34%20AM.png)
#### Title
This is the actual title of your episode in words (ex. Unleashing Revolutionary Architectures with Cats)

![Path](https://cl.ly/2k1Y1F1r0w3O/Screen%20Shot%202017-02-12%20at%201.23.52%20AM.png)
#### Path
This is the permalink for your episode on Goodstuff. You set this by clicking the edit icon (pencil). Make sure the path is the same as the episode number set in `episode` (ex. 103)

![Date](https://cl.ly/061V2P131D1x/Screen%20Shot%202017-02-12%20at%201.25.13%20AM.png)
#### Date
This is the date that the episode is to be published. This will be the date displayed on the website, the feed, and podcast players.

![Layout](https://cl.ly/1A430S3Q0z1t/Screen%20Shot%202017-02-12%20at%201.27.47%20AM.png)
#### Layout
Under **Advanced Settings** you will need to set the `layout` to "episode"

#### Content
This is where you will put *all* of your show notes, links, and images you want to add to your show. You can add this content using the buttons on Siteleaf, add markdown manually, or use their (beta) visual editor.

### Your episode must have the following metadata:

![Metadata](https://cl.ly/0Q392x1X0C2V/Screen%20Shot%202017-02-12%20at%201.29.33%20AM.png)

#### show
This is the url your show uses to post the episode (ex. 3g3q, grownups, atu2, nbsp)

#### mp3
This is where you put the URL of your episode audio (ex. http://podcasts-1.feedpress.co/10588/morningshow-320.mp3). The site only supports mp3s for now.

#### episode
This is the episode number for your show in numerical format (ex. 104).

#### description
This is the short, 256 character description of the show that is displayed on your show's list of episodes and on the home page after your episode is posted. This should be written in plain text and *cannot* include links or other formatting.

#### sponsor
This is *only* the name of the sponsor you want to list on your episode. There is a default value for each show that you can leave if there is no sponsor.

#### sponsor-link
This is the URL for your sponsor.

#### sponsor-copy
This is the short paragraph that accompanies your sponsor name/link. This should be written in plain text and *cannot* include links or other formatting.

***

## Publishing an Episode

![Publish](https://cl.ly/3H0f0J3N1J05/Screen%20Shot%202017-02-12%20at%201.30.35%20AM.png)

Once you have finished adding and saving your latest episode, you will need to publish these changes to the site. This will cause the whole site to be rebuilt and published. Any additional changes will need to follow this same process.

Press the **Publish** button on the top right to publish your episode.

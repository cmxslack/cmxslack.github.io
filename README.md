# cmxslack.github.io
Evangelist Collective Homepage

The community-run CMX slack is a collaborative effort of friendly people who want to empower each other to build a stronger, more inclusive community. For the full schpeel, [read about the project](https://github.com/cmxslack/getting-started).

## Why?
This Slack channel was created to be a side-channel for community managers, community support, technical advocates, evangelists and
organizers. Generally, we aim to be a place you could go with questions like:

* "Hey, who all is going to be at CMX East?"
* "What's the best place to buy t-shirts that fit people?"
* "Does anyone want to co-sponsor a Meetup?"
* "Our Meetup Venue just burned down. Can anyone in Portland host on short notice?"
* "What's the best community platform?"
* "What are your quarterly goals as a community manager?"
* "How much do you travel as an advocate?"
* "What is your corporate conference strategy?"
* "What sticker design is working best for you right now?"
* "I find myself in Chicago and in want of lunch. Anybody hungry?"
* "What extent to you copy-edit your blog content?"
* "Anybody want a job?"
* "Anyone have any advice on starting an Ambassador Program?"

Questions like those get asked and answered every day, along with a lot
of general conversation about advocacy and community management and just plain
palling around. Community Management, developer evangelism and advocacy are relatively new roles, so
in parallel to the community organization activity, a lot of what goes on in
WADE is practitioners figuring out what their own roles mean or how to navigate
making them work in a new place.

## Who can Join?
Our members are generally professionals with the words 'community', 'advocate',
or 'evangelist' in their titles. Organizationally, we usually fall someplace
beneath "Product" on the org chart. Right now looking at the active membership,
we consist mostly of community and event organizers. Many of our members have a
different day job, but organize conferences and/or meetups on the side. We have
several others who are students or who do something else professionally and are
trying to decide if they're interested in switching roles.

Another thing we have in common is that we're generally incentivized to be
cooperative, by which I mean we're very comfortable interacting with, and
exchanging information with our contemporaries at competing organizations, and
being open about the deficiencies in the technology we advocate compared to
competing technology. Despite the religious overtones implied by words like
"evangelism", our professional success is inseparable from our credibility and
especially among software engineers, our credibility rests on candor,
generosity, and sincerity.

## Who can't join?
We've turned down a few membership requests from folks in positions like sales,
marketing, and venture capitalism. It's nothing personal, and we don't have
anything against those things, but we feel that it's important for us to
maintain a certain... simplicity of intention among our members.  At the
moment WADE is genuinely useful as a means of creating ad-hoc dialog between
community and advocacy people in a wide range of organizations, and for that to
continue and grow, we need to make sure that all of our members are cooperative
in nature and both willing and able to help each other out.

That said, we're still figuring out what WADE is and what it could be, so by
all means if you're coming from a marketing or sales or whatever angle, and you
believe that we can help each other, send us an invite request and talk to us.

## Welcome!
I guess the TLDR; is that this is a place where community, event, and advocacy
people can learn from each other, network, and grow.  If that sounds
interesting to you, we'd love to have you join us!


## Contributing

Pull Requests are more than welcome as we coordinate efforts. Here are a few notes to help you along.

### Editing The Site

Some base content lives in `_config.yml` like the data from header and footer. If you want to add or remove a section of the page, you can do so from `_layouts/default.html`. Each section that Jekyll renders is outlined there in a reasonably readable way. You can see the associated content of that section in the `_includes/css/` folder.

For example, this section from `_layouts/default.html`:

     {% include portfolio_grid.html %}

Loads the content defined in `_includes/css/portfolio_grid.html`. Which is pretty nifty. You can edit our site without knowing more than a little HTML.

Other things you'll want to know:

* Our fonts are loaded from `head.html`
* The description under our logo is from `header.html`
* The About section loads from `about.html`

The portfolio is a little tricky: images are automatically loaded from the `img/portfolio` folder. The page that loads is in `_posts`. The mapping of image to post happens in the `_posts` markdown. This all renders thanks to the `modals.html` file which I haven't found a good reason to want to edit.

## Credits

We rock a [MIT License]([LICENSE]). The Jekyll theme is [Freelancer](http://jekyllthemes.org/themes/freelancer/) and icons are from designers on [The Noun Project](http://thenounproject.com). [Matt Brender](http://github.com/mjbrender) made the site.

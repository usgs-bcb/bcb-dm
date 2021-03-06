**Welcome to the "Synthesis Working Groups" on Protected Areas Data and Species Data - two aspects of the USGS Biogeographic Characterization portfolio and foundational data for the National Biogeographic Map.**

I'm excited to see this set of two working groups coming together. Thank you for being patient with (and humoring) us and helping to pull everything together for this on short notice.

For the first group (September 27-28 with a focus on Protected Areas data), we will be meeting at the [Highland City Club](https://www.highlandcityclub.com/) in Boulder, which bills themselves as...

"An inspired place where intellectuals, entrepreneurs, artists and leaders gather to share ideas and shape the landscape of tomorrow."

In my view, that's exactly who we are and what we are about doing.

Logistics-wise, the Protected Areas Group will meet from 08:00 to 16:30. A light breakfast of fruit, pastries, yogurt, and coffee will be served at 08:00 both days. Lunch will also be provided. We are putting together an optional group dinner for the first night, September 27 at 18:00. We'll pick a restaurant together that first morning.

We had to move the second group to the [Impact Hub Boulder](https://impacthubboulder.com/), a slightly different type of collaborative, dynamic space that we're exploring for this type of meetup. Both spaces are close to the vibrant Pearl Street Mall in Boulder.

The Species Data Group has a slightly different daily schedule and will meet from 09:00 to 17:00 both days. Breakfast and lunch will be provided. The optional group dinner is scheduled for October 2 at 18:30. We'll pick the restaurant that morning.

We are very excited to be convening these slightly impromptu meetings through the Earth Science Information Partners, where we are part of a developing experiment into how groups like ours come together to synthesize ideas across our various viewpoints and skills to solve problems related to managing and analyzing scientific data. ESIP is helping us organize and set up the meeting and venue, but we are also helping to develop ideas on how to do this sort of thing as part of the ESIP Lab.

One of the areas we will be experimenting with for both of these meet ups is how we might go about building a living proceedings of our groups, live as we go. We're leveraging some of the great tools that GitHub offers in this regard and have focused everything on a specific repository. We've called it "[bcb-dm](https://github.com/usgs-bcb/bcb-dm)" because it's short and to the point, we are focusing here on a couple aspects of our Biogeographic Characterization portfolio in the USGS, and we're mostly looking at dynamics of how we do the data management stuff that best supports our analytical work.

I realize that some of you who aren't coders in our group may be unfamiliar with GitHub and how things work there. It's simply a tool and not the real focus of our work. We're adopting some of the GitHub stuff so we can dive right into the real work but capture what we do in an effective and usable way as we do it as opposed to the usual laborious process afterwards.

The first page you'll see with the link above shows the readme from the repository, where we've laid out some thinking about what we're doing in these meetings and how to use the tools. This stuff is definitely not set in stone (it's written in markdown), so we'll experiment a little and refine it as we go.

What Steve Aulenbach and I have started in two Jupyter Notebooks contributed to the repository ([Protected Areas](https://github.com/usgs-bcb/bcb-dm/blob/master/Protected-Areas.ipynb) and [Species Data](https://github.com/usgs-bcb/bcb-dm/blob/master/Species%20Data.ipynb)) are definitely works in progress. We're trying there to walk through what we think is the picture of how we manage the data and information assets in the two areas we'll be focusing on with these meetings. I know we've got all kinds of holes in this, and we'll be adding new ideas via pull requests from work we are continuing in coming days.

Out of this work to examine the current state of things in the notebook approach (some text notes with code that probes the reality of what we write up), we are now and will continue to identify specific issues that we want to work on as a group. Some of those issues will get resolved pretty quickly when we get together in a room and folks more familiar with an area can simply educate the rest of us. Some things may require some corrective action to be taken in one area or another. Sometimes, we might break up into smaller groups of a couple people digging in deeper to address one particular challenge, committing some work back, and then sharing what they did.

While we are taking this opportunity to do some foundational work on how we manage these two areas of our data, the point of all of this is to set us up for more efficient, effective, reproducible, traceable, and trustworthy scientific analyses using these data. We need to have a reason behind all the stuff we are doing to produce and manage these core data assets. While some of those reasons come from external stakeholders who use these products for diverse purposes of their own, many of the reasons come from our own science plan and the research questions we've posed. We can't do temporal analyses on how conservation status for species and habitats are changing over time unless we build time into our underlying datasets and manage for it in the integration processes we employ. We can't build time into assets like PAD-US unless we redesign some aspects of the data model, rethink how we are doing versioning, and work on record level management methods.

So, if you are someone who writes code, we hope that you will contribute heavily to our proceedings repo with code. If you are not someone who writes code, we hope you will contribute by writing down ideas and fleshing out challenges through [Issues](https://github.com/usgs-bcb/bcb-dm/issues) and comments. If you tend to focus more on the science questions we're working to ask of these data and sometimes think that all this data management hullabaloo is kind of a distracting pain in the ass, we hope you will contribute (by speaking up and by writing things down in Issues) by asking hard questions. Why are we doing what we're doing the way we're doing it? Why is it important? What questions is it going to help us answer? Is there a new way of thinking about things that might perturb the norm and get us working better? Are we focused on the most important things that are going to reap the biggest payoff for our analytical methods?

A number of you are already starting to jump into the fray here, and I know Steve has been out pestering folks for your GitHub user accounts so we can add you with permissions to write into the repositories under the USGS-BCB organization. Please keep it up in coming days as we prepare for the meetings. If you are puzzled by something, please give me or Steve a call, and we'll puzzle it out together. We by no means have a lock on the ideas here, so please jump in and help us make these two effective and fun times together to get shit done.

Thank you,
Sky

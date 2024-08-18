# Drawn to Scale A Cappella Website

When you're done making changes and stuff just push to master and then do:

```
ssh dts@ssh.ocf.berkeley.edu
```

Ask a previous webmaster for the password. If you don't wanna enter the password every time just put your public key on a new line inside `~/.ssh/authorized_keys`.

Then,

```
cd ~/public_html
git pull
```

and you should see all your changes on drawntoscale.berkeley.edu


# Site Organization
Notes from the previous webmaster (Matthew Cao):
If I haven't razed the entire website to the ground and redesigned it yet, you can tell this is a little bit of a clusterfuck. I mean just look at how the about me pages are made and how they are seperate pages instead of just a jQuery card.

Anyway, let's create some conventions for file naming and asset organization.

### Bio Pages
For bio pages, name them as such:
bio_\<first name>\_\<last name>.html
<br> For example, a bio page for me would be matthew.html

### about.html
Member cards are organized as so: music manager, then administrative director, then secretary, then officers (alphabetically by officer role name), then by non officer (by seniority).

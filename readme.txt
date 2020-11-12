1. Save kinjaextractor.exe to the location where you want your kinja articles to be saved (example C:\Users\<username>\Documents\Kinja)
2. Open command prompt (windows+R cmd)
3. type cd Documents\Kinja
If you want all of your posts type:
4a. kinjaextractor <kinja username>
If you want all of your posts and images, type:
4b. kinjaextractor <kinja username> --images
If you want selected posts, and images
4c.-1. create a <filename>.txt-file with the URLs of the posts you want to save
type:
4c.-2.  kinjaextractor <kinja username> --images --article_list <filename>.txt
If you want all urls:
kinjaextractor <kinja username> --urls-only

Some disclaimer for the code:
Where 'username' is your real Kinja username, where your profile lives, and --images will download the images in your articles if you wish.

The script will create new folders underneath by year.

I take no blame for bandwidth costs or any other ill consequences. Don't run this in an environment where you might break anything.

--------------------------------------

Based on kinja-archive by Srol: https://github.com/Srol/kinja-archive
The extensions of that by macintux: https://github.com/macintux/kinja-archive
And the selective saving by bvdv-dutchengineer: https://github.com/bvdv-dutchengineer/kinja-archive/tree/bvdv-dutchengineer-selective-articles
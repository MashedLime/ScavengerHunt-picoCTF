# ScavengerHunt-picoCTF
Another easy 50 points

Go into inspect and you can get the first two flags in the Source tab.
There's a clue in there as well.
It says, "How can I keep Google from indexing my website?"
I tried a few different endings and eventually got the 3rd part with /robots.txt.
The next clue states that this is an Apache server.
I learned that Apache servers use .htaccess, and used it.
Make sure you're putting it after a slash.
I did it w/o a slash and it didn't work.
The next clue says something about using a Mac and a Store.
I knew it had to be talking about DS store, so I put .DS_Store at the end, giving me the last part of the flag.
All the work put together reads: picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_d375c750}.

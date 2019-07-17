# Some-common-tips-for-taking-a-PoC-
#



Take a screenshot of everything. You might not need it but it’s better than to regret later.
Take relevant screenshots with only the required region. The developer doesn’t need to see your entire desktop and taskbar while you are trying to show him an XSS popup.
Make mute videos and use text editors to type instructions. It is much more convenient.
Write down every step of your process in your text editor, be it information gathering and the information you found, vulnerabilities found, interesting blogs/links that you read to find, test and exploit vulnerabilities, links to automate scripts/exploits you found online, data you found after exploitation, everything!
Use proper folder and file structure.
Make sure that this data is backed up and secure. Use Google Drive, Dropbox, Onedrive, etc. to constantly backup the screenshot folders and VAPT project folders to the cloud.
Also, make sure these are safe and secure, since if someone gets hold of this, he/she will be able to cause critical damage to the organisation and you will get into trouble.

# VAPT Reports: Developer Report v/s Higher Management Report


Let’s look at the key parts of a Detailed Developer Report:
Index of all the vulnerabilities.
Information about what exact URL and parameters are affected.
The payload you used to confirm the vulnerability.
Observations (screenshots/videos) explaining a complete step by step exploitation of each vulnerability.
Outcome (if any) i.e. the data you were able to extract using the vulnerability, commands you were able to run, etc.
Business Impact - A description of the impact of the vulnerability with examples (screenshots/videos).
Recommendations on how to patch the vulnerability.
References about the vulnerability, including links explaining the vulnerability, the patches and the impact.
Let’s look at the key parts of a High Level Management Summary:
Information summarising everything a hacker can do if an attack happens, containing maximum possible impacts of each vulnerability (multiple if they exist).
Information about what exact URL and parameters are affected.
Brief observations containing only the application affected and impact information i.e no step by step guide is required, but only outcome observations.
Detailed business impact with proofs of all kind of information you extracted during the exploitation.
References about the vulnerabilities (not the patches).

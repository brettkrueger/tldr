# pacman --upgrade

> ஆர்ச் லினக்ஸ் தொகுப்பு மேலாளர் பயன்பாடு.
> இதையும் பார்க்கவும்: `pacman`.
> மேலும் விவரத்திற்கு: <https://manned.org/pacman.8>.

- கோப்புகளிலிருந்து ஒன்று அல்லது அதற்கு மேற்பட்ட தொகுப்புகளை நிறுவவும்:

`sudo pacman --upgrade {{நிரல்தொகுப்பு1.pkg.tar.zst/பாதை}} {{நிரல்தொகுப்பு2.pkg.tar.zst/பாதை}}`

- கேட்காமல் ஒரு தொகுப்பை நிறுவவும்:

`sudo pacman --upgrade --noconfirm {{நிரல்தொகுப்பு.pkg.tar.zst/பாதை}}`

- தொகுப்பு நிறுவலின் போது முரண்பட்ட கோப்புகளை மேலெழுதவும்:

`sudo pacman --upgrade --overwrite {{கோப்பு/பாதை}} {{நிரல்தொகுப்பு.pkg.tar.zst/பாதை}}`

- சார்பு பதிப்பு சரிபார்ப்புகளைத் தவிர்த்து, தொகுப்பை நிறுவவும்:

`sudo pacman --upgrade --nodeps {{நிரல்தொகுப்பு.pkg.tar.zst/பாதை}}`

- பாதிக்கப்படக்கூடிய தொகுப்புகளைப் பட்டியலிடுங்கள் (எந்த தொகுப்புகளையும் நிறுவாது):

`pacman --upgrade --print {{நிரல்தொகுப்பு.pkg.tar.zst/பாதை}}`

- உதவியைக் காட்டு:

`pacman --upgrade --help`

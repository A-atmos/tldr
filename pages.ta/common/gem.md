# gem

> ரூபி நிரலாக்க மொழிக்கான தொகுப்பு மேலாளருடன் தொடர்பு கொள்ளுங்கள்.
> மேலும் விவரத்திற்கு: <https://rubygems.org>.

- தொலை ரத்தினங்களைத் தேடி, கிடைக்கக்கூடிய அனைத்து பதிப்புகளையும் காட்டு:

`gem search {{வழக்கமான_வெளிப்பாடு}} --all`

- ரத்தினத்தின் சமீபத்திய பதிப்பை நிறுவவும்:

`gem install {{ரத்தின_பெயர்}}`

- ஒரு ரத்தினத்தின் குறிப்பிட்ட பதிப்பை நிறுவவும்:

`gem install {{ரத்தின_பெயர்}} --version {{1.0.0}}`

- ஒரு ரத்தினத்தின் சமீபத்திய பொருந்தக்கூடிய (SemVer) பதிப்பை நிறுவவும்:

`gem install {{ரத்தின_பெயர்}} --version '~> {{1.0}}'`

- ஒரு ரத்தினத்தைப் புதுப்பிக்கவும்:

`gem update {{ரத்தின_பெயர்}}`

- அனைத்து உள்ளூர் ரத்தினங்களையும் பட்டியலிடுங்கள்:

`gem list`

- ஒரு ரத்தினத்தை நிறுவல் நீக்கவும்:

`gem uninstall {{ரத்தின_பெயர்}}`

- ஒரு ரத்தினத்தின் குறிப்பிட்ட பதிப்பை நிறுவல் நீக்கவும்:

`gem uninstall {{ரத்தின_பெயர்}} --version {{1.0.0}}`
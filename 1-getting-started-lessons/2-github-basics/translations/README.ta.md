# கிட்ஹப் அறிமுகம்

இந்த பாடம் கிட்ஹப் அடிப்படைகளை உள்ளடக்கியது, உங்கள் குறியீட்டில் மாற்றங்களை நடத்த மற்றும் நிர்வகிக்க ஒரு தளம்.

![Iகிட்ஹப் அறிமுகம்](/sketchnotes/webdev101-github.png)
> ஸ்கெட்ச்நோட் [டோமோமி இமுரா](https://twitter.com/girlie_mac)


##  விரிவுரைக்கு முந்தைய வினாடி வினா
[ விரிவுரைக்கு முந்தைய வினாடி வினா](https://happy-mud-02d95f10f.azurestaticapps.net/quiz/3?loc=ta)

## அறிமுகம்

இந்த பாடத்தில், நாங்கள் உள்ளடக்குவோம்:

- உங்கள் இயந்திரத்தில் நீங்கள் செய்யும் வேலையைக் கண்காணித்தல்
- மற்றவர்களுடன் திட்டங்களில் வேலை செய்தல்
- திறந்த மூல மென்பொருள் பங்களிக்க எப்படி

### முன் நிபந்தனைகள்

நீங்கள் தொடங்குவதற்கு முன், கிட் நிறுவப்பட்டதா என்பதை நீங்கள் சரிபார்க்க வேண்டும். முனைய வகை:  
`git --version`

கிட் நிறுவப்படவில்லை என்றால், [கிட் பதிவிறக்க](https://git-scm.com/downloads) . பின்னர், முனையத்தில் உங்கள் உள்ளூர் கிட் சுயவிவரத்தை அமை:

* `git config --global user.name "your-name"`
* `git config --global user.email "your-email"`

கிட் ஏற்கனவே உள்ளமைக்கப்பட்டதா என்பதை சரிபார்க்க நீங்கள் தட்டச்சு செய்யலாம்:
`git config --list`

நீங்கள் ஒரு கிட்ஹப் கணக்கு, ஒரு குறியீட்டு ஆசிரியர் (விஷுவல் ஸ்டுடியோ குறியீடு போன்றவை) வேண்டும், மேலும் உங்கள் முனையத்தைத் திறக்க வேண்டும் (அல்லது: கட்டளை செயலழைப்பு).

நீங்கள் ஏற்கனவே இல்லை என்றால் [github.com](https://github.com/) செல்லவும் மற்றும் ஒரு கணக்கை உருவாக்கவும், அல்லது உள்நுழைந்து உங்கள் சுயவிவரத்தை நிரப்பவும். 


✅  கிட்ஹப் உலகின் ஒரே குறியீடு களஞ்சியம் அல்ல; மற்றவர்கள் இருக்கிறார்கள், ஆனால் கிட்ஹப் நன்கு அறியப்பட்டவர்

### முன்னேற்பாடு செய்தல்

உங்கள் உள்ளூர் இயந்திரத்தில் (மடிக்கணினி அல்லது பிசி) ஒரு குறியீட்டு திட்டத்துடன் ஒரு கோப்புறை மற்றும் கிட்ஹப்பில் ஒரு பொது களஞ்சியம் ஆகிய இரண்டும் உங்களுக்குத் தேவைப்படும், இது மற்றவர்களின் திட்டங்களுக்கு எவ்வாறு பங்களிக்க வேண்டும் என்பதற்கு ஒரு எடுத்துக்காட்டாக இருக்கும். 

---

## குறியீடு மேலாண்மை

சில குறியீட்டு திட்டத்துடன் உள்நாட்டில் ஒரு கோப்புறை உள்ளது என்று வைத்துக்கொள்வோம், மேலும் உங்கள் முன்னேற்றத்தை கிட் - பதிப்பு கட்டுப்பாட்டு அமைப்பு பயன்படுத்தி கண்காணிக்க த் தொடங்க வேண்டும். சிலர் கிட் பயன்படுத்தி உங்கள் எதிர்கால சுய ஒரு காதல் கடிதம் எழுத ஒப்பிட்டு. நாட்கள் அல்லது வாரங்கள் அல்லது மாதங்களுக்குப் பிறகு உங்கள் ஒப்புக்கொள்ளும் செய்திகளைப் படிக்கும்போது, நீங்கள் ஏன் ஒரு முடிவை எடுத்தீர்கள், அல்லது ஒரு மாற்றத்தை "திரும்பப் பெறுகிறீர்கள்" என்பதை நீங்கள் நினைவுகூர முடியும் - அதாவது, நீங்கள் நல்ல "செய்திகளைச் செய்யுங்கள்" என்று எழுதும்போது.

### பணி: ஒரு களஞ்சியத்தை உருவாக்கவும் மற்றும் குறியீட்டை செய்யவும்

1.  **கிட்ஹப் இல் களஞ்சியத்தை உருவாக்கவும்** கிட்ஹப், களஞ்சியங்கள் தாவலை, அல்லது வழிசெலுத்தல் பட்டியில் மேல் வலது இருந்து, **புதிய ரெப்போ ** பொத்தானை கண்டுபிடிக்க.

   1. உங்கள் களஞ்சியத்திற்கு (கோப்புறை) ஒரு பெயரைக் கொடுங்கள்
   1. தேர்ந்தெடுக்கவும் **create repository**.

1. **உங்கள் பணி கோப்புறைக்கு செல்லவும்**. உங்கள் முனையத்தில், கோப்புறைக்கு மாறவும் (கோப்பகம் என்றும் அழைக்கப்படுகிறது) நீங்கள் கண்காணிக்கத் தொடங்க விரும்புகிறீர்கள். மாதிப் படிவம்:

   ```bash
   cd [உங்கள் கோப்புறையின் பெயர்]
   ```

1. **ஒரு கிட் களஞ்சியத்தை துவக்கு**. உங்கள் திட்ட வகை:

   ```bash
   git init
   ```

1. **நிலையை சரிபார்க்கவும்**. உங்கள் களஞ்சிய வகையின் நிலையை சரிபார்க்க:

   ```bash
   git status
   ```

   வெளியீடு இந்த மாதிரி ஏதாவது இருக்க முடியும்:

   ```output
   Changes not staged for commit:
   (use "git add <file>..." to update what will be committed)
   (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   file.txt
        modified:   file2.txt
   ```
   பொதுவாக ஒரு `git status` கட்டளை, கோப்புகளில் _சேமிக்கதயாராக உள்ளது_ ரெப்போஅல்லது நீங்கள் தொடர்ந்து இருக்க விரும்பும் மாற்றங்களைக் கொண்டுள்ளது போன்ற விஷயங்களைஉங்களுக்குச் சொல்கிறது.

1. **கண்காணிப்பு அனைத்து கோப்புகளை சேர்க்க**
   இது ஸ்டேஜிங் கோப்புகள் / ஸ்டேஜிங் பகுதியில் கோப்புகளைச் சேர்ப்பது என்றும் அழைக்கப்படுகிறது.

   ```bash
   git add .
   ```
`git add` பிளஸ் `.` வாதம் உங்கள் கோப்புகள் அனைத்தும் கண்காணிக்க மாறும் என்பதைக் குறிக்கிறது.

1. **கண்காணிப்புக்காக தேர்ந்தெடுக்கப்பட்ட கோப்புகளைச் சேர்க்கவும்**

   ```bash
   git add [கோப்பு அல்லது கோப்புறை பெயர்]
   ```

   ஒரே நேரத்தில் அனைத்து கோப்புகளையும் செய்ய விரும்பாத போது, தேர்ந்தெடுக்கப்பட்ட கோப்புகளை மட்டுமே ஸ்டேஜிங் பகுதியில் சேர்க்க இது உதவுகிறது.

1. **அனைத்து கோப்புகளையும் நிலைநீக்கு**

   ```bash
   git reset
   ```

    இந்த கட்டளை அனைத்து கோப்புகளையும் ஒரே நேரத்தில் நிலைநீக்க உதவுகிறது.


1. **ஒரு குறிப்பிட்ட கோப்பை நிலைநீக்கு**

   ```bash
   git reset [கோப்பு அல்லது கோப்புறை பெயர்]
   ```

    அடுத்த கமிட் செய்ய விரும்பாத ஒரு குறிப்பிட்ட கோப்பை மட்டும் ஒரே நேரத்தில் கட்டமைக்க இந்த கட்டளை நமக்கு உதவுகிறது.

1. **உங்கள் வேலையை த் தொடருதல்**. இந்த கட்டத்தில் நீங்கள் _ஸ்டேஜிங் பகுதி_ என்று அழைக்கப்படும் கோப்புகளை சேர்த்துள்ளீர்கள். உங்கள் கோப்புகளை கிட் கண்காணிக்கும் இடம். மாற்றத்தை நிரந்தரமாக்க, கோப்புகளை _கமிட்_ செய்ய வேண்டும். அவ்வாறு செய்ய நீங்கள் `git commit` கட்டளையுடன் ஒரு _கமிட்_ உருவாக்குகிறீர்கள். ஒரு _கமிட்_ உங்கள் ரெப்போ வரலாற்றில் ஒரு சேமிப்பு புள்ளி யை குறிக்கிறது. _கமிட்_ உருவாக்க பின்வருவனவை தட்டச்சு செய்யவும்:


   ```bash
   git commit -m "first commit"
   ```

    இது உங்கள் கோப்புகள் அனைத்தையும் ஒப்புக்கொள்கிறது, "முதலில் ஒப்புக்கொள்ளுங்கள்" என்ற செய்தியைச் சேர்க்கிறது. எதிர்காலத்தில் செய்திகளைச் செய்ய நீங்கள் என்ன வகையான மாற்றத்தை செய்தீர்கள் என்பதை தெரிவிக்க உங்கள் விளக்கத்தில் இன்னும் விளக்கமாக இருக்க விரும்புகிறீர்கள்.

1. **உங்கள் உள்ளூர் கிட் ரெப்போவை கிட்ஹப் உடன் இணைக்கவும்**. ஒரு கிட் ரெப்போ உங்கள் இயந்திரத்தில் நல்லது, ஆனால் ஒரு கட்டத்தில் நீங்கள் எங்காவது உங்கள் கோப்புகளை காப்புப்பிரதி எடுக்க விரும்புகிறீர்கள், மேலும் உங்கள் ரெப்போவில் உங்களுடன் வேலை செய்ய மற்ற நபர்களை அழைக்கவும் விரும்புகிறீர்கள். அவ்வாறு செய்ய ஒரு பெரிய இடம் கிட்ஹப் ஆகும். நாம் ஏற்கனவே கிட்ஹப்பில் ஒரு ரெப்போவை உருவாக்கியுள்ளோம் என்பதை நினைவில் கொள்ளுங்கள், எனவே நாம் செய்ய வேண்டிய ஒரே விஷயம் கிட்ஹப் உடன் எங்கள் உள்ளூர் கிட் ரெப்போவை இணைக்க வேண்டும். `git remote add` என்ற கட்டளை அதைச் செய்யும். பின்வரும் கட்டளையை தட்டச்சு செய்யவும்:

   > குறிப்பு, நீங்கள் கட்டளையை தட்டச்சு செய்வதற்கு முன், உங்கள் கிட்ஹப் ரெப்போ பக்கத்திற்கு சென்று களஞ்சியத்தை கண்டுபிடிக்கவும். நீங்கள் கீழே உள்ள கட்டளையில் பயன்படுத்துவீர்கள். ```https://github.com/username/repository_name.git``` என்பதை உங்கள் கிட்ஹப் யுஆர்எல் மூலம் மாற்றவும்.


   ```bash
   git remote add origin https://github.com/username/repository_name.git
   ```

 இது ஒரு _தொலை__ அல்லது இணைப்பை உருவாக்குகிறது, "தோற்றம்" என்று பெயரிடப்பட்டது, நீங்கள் முன்பு உருவாக்கிய கிட்ஹப் களஞ்சியத்தை சுட்டிக்காட்டுகிறது.

 1. **கீதுப் க்கு உள்ளூர் கோப்புகளை அனுப்பவும்** இதுவரை நீங்கள் உள்ளூர் ரெப்போ மற்றும் கிட்ஹப் ரெப்போ இடையே ஒரு _இணைப்பு_ உருவாக்கியுள்ளீர்கள். பின்வரும் கட்டளை `git push`உடன் இந்த கோப்புகளை கிட்ஹப் க்கு அனுப்புவோம், இது போன்றது: 
   
   > குறிப்பு, உங்கள் கிளை பெயர் முன்னிருப்பாக வேறுபட்டிருக்கலாம் ```main```.

   ```bash
   git push -u origin main
   ```

      இது உங்கள் "main" கிளையில் உள்ள உங்கள் உறுதிகளை கிட்ஹப் க்கு அனுப்புகிறது.

2. **மேலும் மாற்றங்களைச் சேர்க்க**. நீங்கள் மாற்றங்களைதொடர்ந்து செய்ய விரும்பினால், அவற்றை கிட்ஹப் க்கு தள்ளவிரும்பினால், பின்வரும் மூன்று கட்டளைகளைப் பயன்படுத்த வேண்டும்:

   ```bash
   git add .
   git commit -m "உங்கள் ஒப்புக்கொள்ளும் செய்தியை இங்கே தட்டச்சு செய்யவும்"
   git push
   ```
   > உதவிக்குறிப்பு, நீங்கள் கிட்ஹப்பில் காண்பிக்க விரும்பாத கோப்புகளைத் தடுக்க ஒரு `.gitignore` கோப்பை நீங்கள் ஏற்றுக்கொள்ள விரும்பலாம் - அதே கோப்புறையில் நீங்கள் சேமித்து வைக்கும் குறிப்புகள் கோப்பு போல, ஆனால் ஒரு பொது களஞ்சியத்தில் இடமில்லை. [.gitignore templates](https://github.com/github/gitignore) இல் `.gitignore` கோப்புகளுக்கான வார்ப்புருக்களை நீங்கள் காணலாம்

#### செய்திகளை ஒப்புக்கொள்


ஒரு பெரிய கிட் கமிட் சப்ஜெக்ட் லைன் பின்வரும் வாக்கியத்தை நிறைவு செய்யும்:
பயன்படுத்தப்பட்டால், இந்த உறுதி <உங்கள் பொருள் வரி இங்கே>

பொருள் கட்டாயபயன்படுத்த, தற்போதைய: "மாற்றம்" "மாற்ற" அல்லது "மாற்றங்கள்". 
பொருள் போன்ற, உடலில் (விரும்பினால்) மேலும் கட்டாய பயன்படுத்த, தற்போதைய பதற்றம். உடல் மாற்றம் உந்துதல் சேர்க்க வேண்டும் மற்றும் முந்தைய நடத்தை இந்த மாறாக வேண்டும். நீங்கள் `ஏன்` விளக்குகிறீர்கள், `எப்படி` அல்ல.

✅ கிட்ஹப் சுற்றி உலாவ சில நிமிடங்கள் எடுத்துக் கொள்ளுங்கள். நீங்கள் ஒரு பெரிய ஒப்புக்கொள்ளசெய்தி கண்டுபிடிக்க முடியும்? நீங்கள் ஒரு மிகவும் குறைந்த ஒரு கண்டுபிடிக்க முடியும்? ஒரு கமிட் செய்தியில் தெரிவிக்க மிகவும் முக்கியமான மற்றும் பயனுள்ள தகவல் என்று நீங்கள் நினைக்கிறீர்கள்?

### பணி: ஒத்துழைக்க

கிட்ஹப்பில் விஷயங்களை வைப்பதற்கான முக்கிய காரணம் மற்ற டெவலப்பர்களுடன் ஒத்துழைப்பதை சாத்தியமாக்குகிறது.

## மற்றவர்களுடன் திட்டங்களில் வேலை செய்தல்

உங்கள் களஞ்சியத்தில், பரிந்துரைக்கப்பட்ட சமூக தரங்களுடன் உங்கள் திட்டம் எவ்வாறு ஒப்பிடுகிறது என்பதைப் பார்க்க `நுண்ணறிவு > சமூகம்` செல்லவும்.

   இங்கே உங்கள் கிட்ஹப் ரெப்போ மேம்படுத்த முடியும் என்று சில விஷயங்கள் உள்ளன:
   - **விளக்கம்**. உங்கள் திட்டத்திற்கான விளக்கத்தைச் சேர்த்தீர்களா?
   - **ரீட்மே**. நீங்கள் ஒரு ரீட்மேசேர்த்தீர்களா? கிட்ஹப் ஒரு [ரீட்மே](https://docs.github.com/articles/about-readmes/) எழுதுவதற்கான வழிகாட்டலை வழங்குகிறது
    - **பங்களிப்பு வழிகாட்டுதல்**. உங்கள் திட்டத்தில் [பங்களிப்பு வழிகாட்டுதல்கள்](https://docs.github.com/articles/setting-guidelines-for-repository-contributors/) உள்ளதா, 
   - **நடத்தை விதிகள்**. அ [நடத்தை விதிகள்](https://docs.github.com/articles/adding-a-code-of-conduct-to-your-project/), 
   - **உரிமம்**. ஒருவேளை மிக முக்கியமாக, ஒரு [உரிமம்](https://docs.github.com/articles/adding-a-license-to-a-repository/)?


இந்த வளங்கள் அனைத்தும் புதிய குழு உறுப்பினர்களுக்கு பயனளிக்கும். உங்கள் குறியீட்டைப் பார்ப்பதற்கு முன்பு புதிய பங்களிப்பாளர்கள் பார்க்கும் விஷயங்கள் பொதுவாக உள்ளன, உங்கள் திட்டம் அவர்கள் தங்கள் நேரத்தை செலவழிக்க சரியான இடம் தானா என்பதைக் கண்டறிய.

✅ ரீட்மே கோப்புகள், அவை தயாரிக்க நேரம் எடுத்துக்கொண்டாலும், பெரும்பாலும் பிஸியான பராமரிப்பாளர்களால் புறக்கணிக்கப்படுகின்றன. குறிப்பாக விளக்கப்பட்ட ஒரு உதாரணத்தை நீங்கள் கண்டுபிடிக்க முடியுமா? குறிப்பு: நீங்கள் முயற்சி செய்ய விரும்பும் சில [நல்ல ரீ.ஈ.டி.எம்.இ.க்களை உருவாக்க உதவும் கருவிகள்](https://www.makeareadme.com/) உள்ளன.

### பணி: சில குறியீட்டை ஒன்றுசேர்

பங்களிப்பு ஆவணங்கள் மக்கள் திட்டத்திற்கு பங்களிக்க உதவுகின்றன. நீங்கள் என்ன வகையான பங்களிப்புகளைத் தேடுகிறீர்கள் மற்றும் செயல்முறை எவ்வாறு செயல்படுகிறது என்பதை இது விளக்குகிறது. பங்களிப்பாளர்கள் கீதுப் மீது உங்கள் ரெப்போபங்களிக்க முடியும் படிகள் ஒரு தொடர் மூலம் செல்ல வேண்டும்:

1. **உங்கள் ரெப்போவை ஃபோர்கிங்** ஒருவேளை நீங்கள் மக்கள் உங்கள் திட்டத்தை _ஃபோர்க்_ வேண்டும். ஃபோர்கிங் என்பது அவர்களின் கிட்ஹப் சுயவிவரத்தில் உங்கள் களஞ்சியத்தின் பிரதியை உருவாக்குவதாகும்.
1. **குளோன்**. அங்கிருந்து அவர்கள் தங்கள் உள்ளூர் இயந்திரத்திற்கு திட்டத்தை குளோன் செய்வார்கள். 
1. **ஒரு கிளை உருவாக்க**. நீங்கள் அவர்களின் வேலைக்கு ஒரு _கிளை_ உருவாக்க அவர்களை கேட்க வேண்டும். 
1. **ஒரு பகுதியில் தங்கள் மாற்றத்தை கவனம் செலுத்தவும்**. பங்களிப்பாளர்களை ஒரு நேரத்தில் ஒரு விஷயத்தில் தங்கள் பங்களிப்புகளை ஒருமுகப்படுத்தும்படி கேளுங்கள் - அந்த வழியில் நீங்கள் அவர்களின் வேலையில் _ஒன்றிணைக்க_ வாய்ப்புகளை அதிகமாக உள்ளது. அவர்கள் ஒரு பிழை சரி எழுத கற்பனை, ஒரு புதிய அம்சம் சேர்க்க, மற்றும் பல சோதனைகள் புதுப்பிக்க - நீங்கள் விரும்பினால் என்ன, அல்லது மட்டுமே 3 வெளியே 2 செயல்படுத்த முடியும், அல்லது 3 மாற்றங்கள் 1?

✅ நல்ல குறியீட்டை எழுதுவதற்கும் அனுப்புவதற்கும் கிளைகள் குறிப்பாக முக்கியமான ஒரு சூழ்நிலையை கற்பனை செய்து பாருங்கள். வழக்குகள் என்ன பயன் என்று நீங்கள் நினைக்கலாம்?

> குறிப்பு, நீங்கள் உலகில் பார்க்க விரும்பும் மாற்றமாக இருங்கள், உங்கள் சொந்த வேலைக்கும் கிளைகளை உருவாக்குங்கள். நீங்கள் செய்யும் எந்தவொரு உறுதிப்படமும் நீங்கள் தற்போது "சரிபார்க்கப்பட்ட" கிளையில் செய்யப்படும். எந்த கிளை என்று பார்க்க `git status` பயன்படுத்தவும்.

பங்களிப்பாளர் பணிப்பாய்வின் மூலம் செல்லலாம். பங்களிப்பாளர் ஏற்கனவே _ஃபோர்க்_ மற்றும் _குளோன்_ ரெப்போவை வைத்திருக்கிறார் என்று வைத்துக்கொள்ளுங்கள், எனவே அவர்கள் தங்கள் உள்ளூர் இயந்திரத்தில் வேலை செய்ய தயாராக ஒரு கிட் ரெப்போவை வைத்திருக்கிறார்கள்:

1. **ஒரு கிளை உருவாக்க**. `git branch` என்ற கட்டளையைப் பயன்படுத்தி, அவர்கள் பங்களிக்க வேண்டிய மாற்றங்களைக் கொண்ட ஒரு கிளையை உருவாக்கவும்:

   ```bash
   git branch [கிளை பெயர்]
   ```

1. **வேலை செய்யும் கிளைக்கு மாறவும்**. குறிப்பிட்ட கிளைக்கு மாறி, பணி கோப்பகத்துடன் புதுப்பிக்கவும் `git switch`:

   ```bash
   git switch [கிளை பெயர்]
   ```

1. **வேலை செய்யுங்கள்**. இந்த கட்டத்தில் நீங்கள் உங்கள் மாற்றங்களை சேர்க்க விரும்புகிறீர்கள். பின்வரும் கட்டளைகளுடன் அதைப் பற்றி கிட் சொல்ல மறக்க வேண்டாம்:

   ```bash
   git add .
   git commit -m "என் மாற்றங்கள்"
   ```

   உங்கள் நலனுக்காகவும், நீங்கள் உதவி செய்யும் ரெப்போவின் பராமரிப்பாளராகவும், உங்கள் உறுதிக்கு ஒரு நல்ல பெயரைக் கொடுப்பதை உறுதி செய்யுங்கள்.

1.**உங்கள் வேலையை `main` கிளையுடன் இணைக்கவும்**. ஒரு கட்டத்தில் நீங்கள் வேலை செய்து விட்டீர்கள், உங்கள் வேலையை `main` கிளையுடன் இணைக்க விரும்புகிறீர்கள். `main` கிளை இதற்கிடையில் மாறியிருக்கலாம், எனவே பின்வரும் கட்டளைகளுடன் சமீபத்தியதை முதலில் புதுப்பிக்கவும்:

   ```bash
   git switch main
   git pull

   ```

   இந்த கட்டத்தில், உங்கள் பணிக்கிளையில் மாற்றங்கள் எளிதாக _இணைவுகள்_ செய்ய முடியாத சூழ்நிலைகளில் ஏதேனும் _இணை_, இருப்பதை உறுதி செய்ய விரும்புகிறீர்கள். எனவே பின்வரும் கட்டளைகளை இயக்கவும்:

   ```bash
   git switch [கிளை பெயர்]
   git merge main
   ```


இது உங்கள் கிளையில் `main` இருந்து அனைத்து மாற்றங்களையும் கொண்டு வரும் மற்றும் வட்டம் நீங்கள் தொடர முடியும். இல்லையெனில்,கிட்  _confused_ எங்கே என்று விஎஸ் குறியீடு உங்களுக்கு சொல்லும், மேலும் எந்த உள்ளடக்கம் மிகவும் துல்லியமானது என்று சொல்ல பாதிக்கப்பட்ட கோப்புகளை மாற்றவும்.

1. 1. **உங்கள் வேலையை கிட்ஹப்**க்கு அனுப்பவும். உங்கள் வேலையை கிட்ஹப் க்கு அனுப்புவது என்பது இரண்டு விஷயங்களைக் குறிக்கிறது. உங்கள் கிளையை உங்கள் ரெப்போவுக்குத் தள்ளி, பின்னர் ஒரு பேஆர், புல் கோரிக்கையைத் திறக்கவும்.

   ```bash
   git push --set-upstream origin [கிளை பெயர்]
   ```
   மேலே கட்டளை உங்கள் முட்கரண்டி ரெப்போ கிளை உருவாக்குகிறது.

1. **ஒரு பேஆர்** திறக்கவும். அடுத்து, நீங்கள் ஒரு பேஆர் ஐ திறக்க விரும்புகிறீர்கள். நீங்கள் கிட்ஹப் மீது ஃபோர்க்செய்யப்பட்ட ரெப்போவுக்கு வழிசெலுத்துவதன் மூலம் அதைச் செய்கிறீர்கள். நீங்கள் ஒரு புதிய பேஆர் ஐ உருவாக்க விரும்புகிறீர்களா என்று கேட்கும் கிட்ஹப்பில் ஒரு அறிகுறியைப் பார்ப்பீர்கள், அதை கிளிக் செய்து, செய்தி தலைப்பை மாற்றக்கூடிய ஒரு இடைமுகத்திற்கு நீங்கள் அழைத்துச் செல்லப்படுகிறீர்கள், அதற்கு மிகவும் பொருத்தமான விளக்கத்தை க்கொடுங்கள். இப்போது நீங்கள் ஃபோர்க் செய்த ரெப்போவின் பராமரிப்பாளர் இந்த பேஆர் ஐப் பார்ப்பார், _விரல்கள் கடந்து_ அவர்கள் பாராட்டுவார்கள் மற்றும் உங்கள் பேஆர் ஐ இணைப்பார்கள். நீங்கள் இப்போது ஒரு பங்களிப்பாளராக இருக்கிறீர்கள், நீங்கள் :)

1. **சுத்தம்**. நீங்கள் வெற்றிகரமாக ஒரு பேஆர் ஐ இணைத்த பிறகு _சுத்தம்_ நல்ல நடைமுறையாகக் கருதப்படுகிறது. உங்கள் உள்ளூர் கிளை மற்றும் நீங்கள் கிட்ஹப் க்கு தள்ளிய கிளை இரண்டையும் சுத்தம் செய்ய விரும்புகிறீர்கள். முதலில் பின்வரும் கட்டளையுடன் அதை உள்நாட்டில் நீக்குவோம்: 

   ```bash
   git branch -d [கிளை பெயர்]
   ```

   நீங்கள் அடுத்த ஃபோர்க்செய்யப்பட்ட ரெப்போவிற்கு கிட்ஹப் பக்கம் செல்வதை உறுதி செய்து, நீங்கள் அதை தள்ளிய தொலைதூர கிளையை அகற்றவும்.

`புல் கோரிக்கை` ஒரு முட்டாள்தனமான சொல் போல் தெரிகிறது, ஏனென்றால் உண்மையில் நீங்கள் திட்டத்தில் உங்கள் மாற்றங்களை தள்ள விரும்புகிறீர்கள். ஆனால் பராமரிப்பாளர் (திட்ட உரிமையாளர்) அல்லது முக்கிய குழு திட்டத்தின் "முக்கிய" கிளையுடன் இணைப்பதற்கு முன் உங்கள் மாற்றங்களை கருத்தில் கொள்ள வேண்டும், எனவே நீங்கள் உண்மையில் ஒரு பராமரிப்பவரிடமிருந்து ஒரு மாற்ற முடிவைக் கோருகிறீர்கள்.  

ஒரு இழு கோரிக்கை மதிப்புரைகள், கருத்துக்கள், ஒருங்கிணைந்த சோதனைகள் மற்றும் பலவற்றுடன் ஒரு கிளையில் அறிமுகப்படுத்தப்பட்ட வேறுபாடுகளை ஒப்பிட்டு விவாதிக்க ும் இடம். ஒரு நல்ல இழுப்பு கோரிக்கை ஒரு ஒப்புக்கொள்ளும் செய்தி போன்ற கிட்டத்தட்ட அதே விதிகளைப் பின்பற்றுகிறது. எடுத்துக்காட்டாக, உங்கள் வேலை ஒரு சிக்கலைத் சரிசெய்யும்போது, சிக்கல் டிராக்கரில் உள்ள ஒரு பிரச்சினைக்கு நீங்கள் ஒரு குறிப்பைச் சேர்க்கலாம். இது ஒரு `#` பயன்படுத்தி செய்யப்படுகிறது, அதைத் தொடர்ந்து உங்கள் பிரச்சினையின் எண்ணிக்கை. உதாரணமாக `#97`.

🤞அனைத்து காசோலைகளும் கடந்து, திட்ட உரிமையாளர்(கள்) உங்கள் மாற்றங்களை திட்டத்தில் இணைக்க வேண்டும் என்று விரல்கள் கடந்து விட்டன🤞

கிட்ஹப்பில் உள்ள தொடர்புடைய தொலைநிலை கிளையிலிருந்து அனைத்து புதிய ஒப்புக்களுடன் உங்கள் தற்போதைய உள்ளூர் பணிகிளையைப் புதுப்பிக்கவும்:

`git pull`

## திறந்த மூலத்திற்கு எவ்வாறு பங்களிக்க வேண்டும்

முதலில், உங்களுக்கு ஆர்வமுள்ள கிட்ஹப்பில் ஒரு களஞ்சியத்தை (அல்லது **ரெப்போ**) காணலாம், அதற்கு நீங்கள் ஒரு மாற்றத்தை பங்களிக்க விரும்புகிறீர்கள். அதன் உள்ளடக்கங்களை உங்கள் இயந்திரத்தில் நகலெடுக்க விரும்புகிறீர்கள்..

✅  'தொடக்க நட்பு' ரெப்போஸைக் கண்டுபிடிக்க ஒரு நல்ல வழி ['நல்ல முதல் பிரச்சினை' என்ற குறிச்சொல்மூலம் தேடுவதாகும்](https://github.blog/2020-01-22-browse-good-first-issues-to-start-contributing-to-open-source/).

![உள்ளூரில் ஒரு ரெப்போவை நகலெடுக்கவும்](../images/clone_repo.png)

குறியீட்டை நகலெடுக்க பல வழிகள் உள்ளன. ஒரு வழி களஞ்சியத்தின் உள்ளடக்கங்களை "குளோன்" செய்வது, HTTPஎஸ், எஸ்எஸ்ஹெச், அல்லது கிட்ஹப் சிஎல்ஐ (கட்டளை வரி இடைமுகம்) பயன்படுத்தி. 

உங்கள் முனையத்தைத் திறந்து களஞ்சியத்தை இவ்வாறு குளோன் செய்யுங்கள்:
`git clone https://github.com/புரொஜக்ட்யுஆர்எல்`

திட்டத்தில் வேலை செய்ய, சரியான கோப்புறைக்கு மாறவும்:
`cd புரொஜக்ட்யுஆர்எல்`

நீங்கள் [கோட்ஸ்பேஸ்](https://github.com/features/codespaces), கிட்ஹப்பின் உட்பொதிக்கப்பட்ட குறியீடு ஆசிரியர் / கிளவுட் மேம்பாட்டு சூழல் அல்லது [கிட்ஹப் டெஸ்க்டாப்](https://desktop.github.com/) பயன்படுத்தி முழு திட்டத்தையும் திறக்கலாம்

இறுதியாக, நீங்கள் ஒரு ஜிப் செய்யப்பட்ட கோப்புறையில் குறியீட்டைப் பதிவிறக்கலாம்.

### கிட்ஹப் பற்றி இன்னும் சில சுவாரஸ்யமான விஷயங்கள்

நீங்கள் கீதுப்-இல் உள்ள எந்தவொரு பொது களஞ்சியத்தையும் நட்சத்திர, பார்வை மற்றும் /அல்லது "முட்கரண்டி" செய்யலாம். மேல்-வலது கீழ்-கீழ் மெனுவில் உங்கள் நட்சத்திரகளஞ்சியங்களை நீங்கள் காணலாம். இது புக்மார்க்கிங் போன்றது, ஆனால் குறியீட்டுக்கு.

திட்டங்கள் ஒரு சிக்கல் டிராக்கர் வேண்டும், பெரும்பாலும் "சிக்கல்கள்" தாவலில் கிட்ஹப் இல்லையெனில் சுட்டிக்காட்டப்படாவிட்டால், அங்கு மக்கள் திட்டம் தொடர்பான சிக்கல்களைவிவாதிக்கிறார்கள். மற்றும் புல் கோரிக்கைகள் தாவல் மக்கள் விவாதிக்க மற்றும் முன்னேற்றத்தில் இருக்கும் மாற்றங்களை மதிப்பாய்வு எங்கே உள்ளது.

திட்டங்கள் மன்றங்கள், அஞ்சல் பட்டியல்கள் அல்லது ஸ்லாக், டிஸ்ட்டர் அல்லது ஐஆர்சி போன்ற அரட்டை சேனல்களிலும் விவாதம் நடத்தலாம்.

✅ உங்கள் புதிய கிட்ஹப் ரெப்போவைச் சுற்றி பாருங்கள் மற்றும் சில விஷயங்களை முயற்சிக்கவும், எடிட்டிங் அமைப்புகள், உங்கள் ரெப்போவில் தகவலைச் சேர்த்தல், மற்றும் ஒரு திட்டத்தை உருவாக்குதல் (ஒரு கன்பன் பலகை போன்றது). நீங்கள் செய்ய முடியும் நிறைய இருக்கிறது!

---

## 🚀 அறைகூவல் 

ஒருவருக்கொருவர் குறியீட்டில் வேலை செய்ய ஒரு நண்பருடன் ஜோடி சேரவும். ஒரு திட்டத்தை கூட்டாக உருவாக்கவும், ஃபோர்க் குறியீடு, கிளைகளை உருவாக்கவும், மாற்றங்களை இணைக்கவும்.

## விரிவுரைக்குப் பிந்தைய வினாடி வினா
[விரிவுரைக்குப் பிந்தைய வினாடி வினா](https://happy-mud-02d95f10f.azurestaticapps.net/quiz/4?loc=ta)

## ஆய்வு & சுய ஆய்வு

மேலும் வாசிக்க [திறந்த மூல மென்பொருளுக்கு பங்களிப்பு](https://opensource.guide/how-to-contribute/#how-to-submit-a-contribution). 

[கிட் ஏமாற்றுதாள்](https://training.github.com/downloads/github-git-cheat-sheet/).

பயிற்சி, பயிற்சி, பயிற்சி. கிட்ஹப் [lab.github.com](https://lab.github.com/) வழியாக கிடைக்கும் சிறந்த கற்றல் பாதைகளைக் கொண்டுள்ளது:

- [கிது முதல் வாரம்](https://lab.github.com/githubtraining/first-week-on-github)


நீங்கள் இன்னும் மேம்பட்ட ஆய்வகங்கள் காண்பீர்கள். 

##  வகுத்தமைத்தல் 

முழுமையான [கிட்ஹப் பயிற்சி ஆய்வகத்தில் முதல் வாரம்](https://lab.github.com/githubtraining/first-week-on-github)
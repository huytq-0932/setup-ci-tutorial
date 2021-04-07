# 1. Setup Pull Request Title Checker Tool (For Trainees)
- Create file .github/workflows/pull_request_title_conventions.yml 
- Copy content of [file](https://github.com/awesome-academy/setup-ci-tutorial/blob/main/.github/workflows/pull_request_title_conventions.yml) into recent created file.

# 2. Setup Pull Request Template (For Trainees)
- Create file .github/pull_request_template.md
- Copy content of [file](https://github.com/awesome-academy/setup-android-project-for-trainees/blob/main/.github/pull_request_template.md) into recent created file.

# 3. Setup CI tutorial for Trainee

**Setup Sun*CI**
Create file .sun-ci.yml with [template](https://github.com/awesome-academy/template-ci/blob/main/.sun-ci.yml) to your project root

**Edit environment**
- Replace info chatwork box's id in ROOM_ID by your box's id
- Replace info chatwork accounts in MEMBERS by your team's chatwork accounts
```
 environment:
      # This is Android review pull request box 
      ROOM_ID: "NEED_TO_REPLACE"
      # Insert the chatwork accounts which you want to mention when the pull request was verified
      MEMBERS: "[To:1234567] Tran Quang Huy"
```
# 3. Review
- Add changes and create pull request
- Send to Trainers review  

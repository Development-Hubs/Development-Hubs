# Publish your GitHub profile step by step

Your GitHub username is `Development-Hubs`. GitHub only displays a profile README when a public repository has exactly the same name.

## Step 1: Download and extract the package

1. Download `Shahzad-Tanveer-GitHub-Profile.zip`.
2. Right-click the ZIP file and select **Extract All**.
3. Open the extracted folder.
4. Confirm it contains:

```text
README.md
SETUP.md
assets/
└── banner.png
```

## Step 2: Create the special profile repository

1. Open `https://github.com/new`.
2. Make sure the owner is **Development-Hubs**.
3. Enter `Development-Hubs` as the repository name. Capitalization and spelling must match your username.
4. GitHub should show a message that this is a special profile repository.
5. Add this description:

```text
Senior Full Stack Developer | Laravel, Enterprise ERP, Mobile Apps & Cloud
```

6. Select **Public**.
7. Do not select **Add a README file**.
8. Keep `.gitignore` set to **None**.
9. Keep the license set to **None**.
10. Select **Create repository**.

## Step 3: Upload the profile files using GitHub

1. Open your new `Development-Hubs/Development-Hubs` repository.
2. Select **uploading an existing file**.
3. Open the extracted package folder on your computer.
4. Select `README.md`, `SETUP.md`, and the complete `assets` folder.
5. Drag them together into GitHub's upload area.
6. Wait until GitHub lists these files:

```text
README.md
SETUP.md
assets/banner.png
```

7. In the commit message, enter:

```text
Create professional GitHub profile
```

8. Select **Commit changes**.
9. Open `https://github.com/Development-Hubs`.
10. Refresh the page. The new profile README should appear below your profile header.

## Step 4: If the banner does not display

1. Open the profile repository.
2. Confirm the image exists at `assets/banner.png`.
3. Confirm the first image inside `README.md` uses:

```html
<img src="./assets/banner.png" alt="Shahzad Tanveer — Senior Full Stack Developer" width="100%" />
```

4. File and folder names are case-sensitive. Use lowercase `assets` and `banner.png`.

## Step 5: Update your GitHub profile information

Use this profile information:

- **Name:** Shahzad Tanveer
- **Bio:** Senior Full Stack Developer | Laravel, ERP, Mobile Apps & Cloud
- **Company:** Rozana Manpower & Recruitment Company
- **Location:** Doha, Qatar
- **Website:** https://weberpsolutions.com/
- **LinkedIn:** https://www.linkedin.com/in/shahzad-tanveer07/

To add it:

1. Open your GitHub profile.
2. Select **Edit profile**.
3. Enter the information above.
4. Select **Save**.

## Step 6: Hide weak pinned repositories

1. Open `https://github.com/Development-Hubs`.
2. Select **Customize your pins**.
3. Remove `TestRepo`.
4. Remove `github-final-project` after you have better portfolio repositories.
5. Select **Save pins**.

Removing a pin does not delete the repository.

## Step 7: Prepare strong public repositories

Create sanitized portfolio repositories that contain no employer source code, private business logic, credentials, customer information, or production data:

1. `laravel-erp-starter`
2. `recruitment-workflow-demo`
3. `laravel-accounting-api`
4. `react-native-business-app`
5. `flutter-business-app-demo`
6. `python-automation-toolkit`
7. `shopify-integration-demo`
8. `wordpress-business-theme`

Each repository should contain:

- A clear project summary and problem statement
- Screenshots or a short demo GIF
- Architecture and database diagrams
- Technology stack
- Local installation instructions
- Test or demo credentials using fake data
- API documentation where applicable
- Security decisions and known tradeoffs
- License and contribution guidance

## Step 8: Pin the best repositories

After the repositories contain real work:

1. Open your GitHub profile.
2. Select **Customize your pins**.
3. Pin the four portfolio repositories.
4. Remove `TestRepo` and the course-template repository from the pinned section.

## Step 9: Keep the profile active

Every week, make meaningful improvements such as:

1. Add a real feature to a demonstration project.
2. Write or improve automated tests.
3. Improve project documentation.
4. Fix genuine open-source issues.
5. Open useful pull requests.
6. Answer technical questions in GitHub Discussions.

Do not create empty commits merely to color the contribution graph.

## Important

- Do not upload source code owned by your employer or clients.
- Never commit `.env` files, API keys, passwords, database backups, passports, candidate documents, or customer records.
- GitHub activity cannot be improved honestly by artificial commits. Publish useful projects and make consistent, meaningful updates.
- The language card will only become representative after real source-code repositories are public.

## Earn official GitHub achievements

GitHub controls official profile achievements. They cannot be manually inserted into the README. Earn them through genuine activity:

- **Pull Shark:** Open pull requests that are merged.
- **Pair Extraordinaire:** Co-author commits that are merged into pull requests.
- **Galaxy Brain:** Provide accepted answers in GitHub Discussions.
- **Quickdraw:** Close an issue or pull request shortly after opening it when appropriate.
- **Starstruck:** Build a useful public repository that receives stars.
- **Public Sponsor:** Sponsor open-source maintainers through GitHub Sponsors.
- **YOLO:** Merge a pull request without a review only when it is safe and appropriate.

Avoid spam, artificial commits, fake stars, meaningless pull requests, or unsafe merges. Strong public projects and helpful open-source contributions improve both achievements and recruiter confidence.

### Crowdfunding Platform

**Context:**  
Crowdfunding platforms empower individuals and organizations to raise funds for various causes, projects, or startups by collecting donations from a broad audience. A seamless and engaging platform fosters more successful campaigns by making it easy for users to start, promote, and track their funding efforts.

**Project Goal:**  
Develop a crowdfunding platform where users can create and manage campaigns, track donations in real-time, and engage with supporters through interactive features like live comments and updates.

### Key Frontend Features

#### 1. **Interactive Campaign Creation Wizard**

- **Feature Description:** Allow users to create campaigns through a step-by-step guided form. They can add descriptions, goals, and media (images, videos) using drag-and-drop uploads and get live previews of their campaign page before publishing.
- **Frontend Focus:**
  - **Drag-and-Drop Media Uploads:** Design a smooth drag-and-drop interface for users to upload images and videos. Integrate progress bars for uploads and real-time error handling for large or unsupported files.
  - **Live Campaign Preview:** Implement a live preview of the campaign page that updates as users fill out the form, allowing them to see the final look of their campaign in real time.
  - **Milestone Tracking:** Provide an intuitive interface for users to add fundraising milestones (e.g., 25%, 50% funded) with clear visual indicators, offering both campaigners and donors an easy way to track progress.

#### 2. **Donation Tracking Dashboard**

- **Feature Description:** Build a donation tracking dashboard for both campaign creators and donors. It should display key stats like total funds raised, number of donors, and progress toward the fundraising goal.
- **Frontend Focus:**
  - **Real-Time Progress Bars:** Use animated progress bars that update in real-time as donations come in. Include percentage displays and customizable color schemes based on the campaign's branding.
  - **Donation Statistics:** Design an engaging stats overview showing the total amount raised, number of backers, average donation, and time left for the campaign. Implement smooth transitions between daily, weekly, and monthly views of donation activity.
  - **Supporter Badges:** Reward top contributors with visually appealing supporter badges, displayed next to their comments or profiles, enhancing the sense of community and recognition.

#### 3. **Supporter Interaction Features**

- **Feature Description:** Encourage engagement between campaign creators and supporters through a live comment section, real-time updates, and supporter recognition. This builds trust and transparency, improving the likelihood of successful campaigns.
- **Frontend Focus:**
  - **Live Comment Section:** Design a real-time comment feed where supporters can leave messages, ask questions, and share encouragement. Include rich text editing for supporters to add links or media in their comments.
  - **Interactive Update Feed:** Enable campaign creators to post updates (e.g., milestones achieved, progress reports) with the option to attach images or videos. Updates should automatically notify supporters, and each post can be liked or commented on.
  - **Personalized Notifications:** Implement push notifications for supporters to receive updates on the campaigns they've donated to, such as new milestones or reward tiers being unlocked.

#### 4. **Rewards & Incentive Mechanism** (Optional)

- **Feature Description:** Allow campaigners to set reward tiers based on donation amounts, incentivizing higher contributions.
- **Frontend Focus:**
  - **Reward Tiers Visualization:** Display reward tiers in an engaging layout (e.g., stacked cards or grids), highlighting what each supporter receives for contributing different amounts. Include animations that highlight unlocked rewards.
  - **Dynamic Countdown:** For time-sensitive rewards (e.g., early-bird discounts), implement dynamic countdown timers to create a sense of urgency.

---
icon: bullhorn
---

# Calls

**Token Calls** is a powerful feature on DYORHub that lets users publicly **predict the future price** (or market cap) of a token — and be **held accountable** for it.

Calls are timestamped, tied to the token’s exact price at the moment of submission, and evaluated over time. It’s not just about saying _“this will pump”_ — it’s about being precise, clear, and transparent.

### 🧠 How It Works

To make a prediction, click the **“Make a Prediction”** button on a token's detail page. You’ll be asked to specify:

* **Target Metric**: Predict either the _market cap_ or _price._
* **Prediction Type**: Choose percentage gain, multiple (e.g. 2x), or an exact target value.
* **Target Timeframe**: When you believe the target will be reached (e.g. 1 week, 1 month).
* **Explanation** _(optional)_: Provide a short rationale behind your prediction.



Here is the current prediction form:

<figure><img src="../.gitbook/assets/Screenshot 2025-05-04 at 17.13.45.png" alt="" width="188"><figcaption><p>Price prediction creation form</p></figcaption></figure>

### 💬 Social Features

When a DYORHub user makes a prediction, their **Token Call** is automatically embedded into the **Community Discussion** section — appearing just like a regular comment, but with enhanced visual and functional elements.

<figure><img src="../.gitbook/assets/Screenshot 2025-05-04 at 17.21.11.png" alt=""><figcaption><p>Sample call on DYORHub</p></figcaption></figure>

### 📄 Call Detail Page

Every prediction made on DYORHub comes with its own **Call Detail Page** — a transparent, data-rich view of the prediction and its outcome.

<figure><img src="../.gitbook/assets/Screenshot 2025-05-04 at 17.11.44.png" alt=""><figcaption></figcaption></figure>

Here’s what you’ll find on a Call Detail Page:

* 📈 **Performance Chart**: A real-time price or market cap chart showing the prediction's trajectory and whether the target was hit within the specified timeframe.
* 🎯 **Target Metrics**: The prediction’s target (e.g., $200K market cap), initial value at the time of submission, and whether it was successfully reached.
* ⏱️ **Timing**: The exact date and time the call was made and the deadline for the prediction.
* 📢 **User Commentary**: The original comment or explanation from the predictor, shown just like a post in the Community Discussion.
* 🧠 **Success Indicator**: A clear success/fail badge, along with the calculated **price multiplier** (e.g. 2.02x increase).
* 🔁 **Social Features**: Other users can reply, upvote/downvote, **tip the caller**, or **share the prediction** with a visual preview on Twitter/X.

These pages make it easy to **track the accuracy** of calls over time and give proper recognition to users who consistently get it right.

### 🌍 Token Calls Explorer

The [**Token Calls Explorer**](https://dyorhub.xyz/token-calls) is a public dashboard that showcases **all price predictions** made by DYORHub users. It’s where you can explore the accuracy, timing, and performance of calls across the entire platform.

You can browse:

* **All Calls**
* **Pending Calls**
* **Successful Calls**
* **Failed Calls**

Each row displays key information including:

* **User & Token**
* **Status** (✅ success, ⏳ pending, ❌ failed)
* **Reference Market Cap** (when the call was made)
* **Target Market Cap** (or price)
* **Change (Multiplier)** – how much the token moved
* **Time of Call** and **Prediction Deadline**

You can also filter by **date range**, or search by specific **user** or **token**.

<figure><img src="../.gitbook/assets/Screenshot 2025-05-04 at 17.18.06.png" alt=""><figcaption></figcaption></figure>

This explorer makes it easy to identify top performers, follow active predictors, and see which tokens are being watched closely by the community.

### 🏆 Leaderboard

Top users with a strong success rate are featured on the [**Token Call Leaderboard**](https://dyorhub.xyz/leaderboard?category=tokenCalls\&page=1), showcasing those who make consistently valuable predictions. This promotes credibility, transparency, and merit-based recognition.

{% hint style="info" %}
Score calculation is based on this formula:

&#x20;`Adjusted Score = (Successful Calls / Total Calls) * log(Total Calls + 1)`

* Success Rate: Measures the accuracy of the user's calls.
* Total Calls: Accounts for the user's activity level.
* log(Total Calls + 1): Applies a logarithmic scale to dampen the effect of high call volumes, preventing users from gaming the system by sheer quantity.

So basically this formula keeps success rate important but rewards consistent contributors more.\
Also the log() function dampens the effect of total calls so that quality still matters.
{% endhint %}

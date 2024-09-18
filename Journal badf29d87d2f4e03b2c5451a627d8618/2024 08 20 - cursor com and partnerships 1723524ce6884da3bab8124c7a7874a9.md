# 2024/08/20 - cursor.com and partnerships

Date: August 20, 2024
Description: Light is making progress in partnerships within the crypto space, emphasizing the importance of showcasing unique ecosystems rather than superficial collaborations. The focus is on creating an accessible platform for users to engage with crypto projects and chains. Additionally, the author experimented with the cursor tool but found its pricing to be unfavorable, despite the potential of unlimited slow queries.

## Light Progress

### Today’s Todos

- [ ]  Implement the DAG synced w/ `contracts` `flow` `python` `rust`
- [ ]  First tx operation conducted w/ the DAG implementation
- [x]  Begin `/changelog` and post the first one on `blog` `changelog` too

Completed [https://light.so/blog](https://light.so/blog) - will lead to partnership announcements like the one below. (Thank you to [0xOzh](https://x.com/0xOzh) for the design 🙇‍♂️) 

![image.png](https://assets.light.so/social/end-of-tweet.png)

One thing that I’m (personally) excited about Light is the power of partnerships in crypto as a chain abstraction protocol. Unlike most partnerships in crypto that are the [sake of partnerships](https://x.com/unhappiimochii/status/1805450018847125647), we have an opportunity to highlight and showcase the underlying unique ecosystems of chains, projects, and people - which I think is exciting. Thoughts here: [https://typefully.com/t/fm3G8uW](https://typefully.com/t/fm3G8uW)

### What Light is focused on

<aside>
💡 Light is focused on creating the most accessible layer to experience and harness the power of crypto for most people - and that starts w/ supporting as many projects, chains, and actions as possible with little-to no barriers.

</aside>

### Github *dumb* PR of the day

[https://github.com/LightDotSo/LightDotSo/pull/2260](https://github.com/LightDotSo/LightDotSo/pull/2260)

What nobody will literally notice about Light is that all of the assets are stored under an [R2](https://www.cloudflare.com/developer-platform/r2/) (S3-compatible service by [eastdakota](https://x.com/eastdakota)) but are backed up to [ardrive](https://ardrive.io/), so all of assets are [recoverable](https://github.com/LightDotSo/LightDotSo/blob/2ddaf1933ce360df3a2dcf5f22f3eb34c3b91593/assets/meta/blog.json#L48) and stored in perpetuity in the event that a storage service or X goes down. ex) [R2](https://assets.light.so/blog/announcements/introducing-light.png) ↔ [Arweave](https://arweave.net/4Rb2ZekeLIxo6CtLVlLzUFvAPqXBwSslXPj-46WZALA)

### Some Related Notes

Used [cursor](https://cursor.com) for the first time! I’m using it together w/ [https://openrouter.ai/](https://openrouter.ai/) (can pay w/ crypto which i think is really cool) - going to use it over the next couple of days to see if I like it and how a product can overcome being a “GPT Wrapper”. 

Update: Tried it out but, the [pricing](https://www.cursor.com/pricing) is really bad - $20 / Month is just not a good deal for most if limited by 500 fast queries. But the slow queries are unlimited - perhaps trying that out?

![Screenshot 2024-08-20 at 7.58.35 PM.png](2024%2008%2020%20-%20cursor%20com%20and%20partnerships%201723524ce6884da3bab8124c7a7874a9/Screenshot_2024-08-20_at_7.58.35_PM.png)
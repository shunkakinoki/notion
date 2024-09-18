# 2024/09/11 - Dependencies, dependencies, dependencies

Date: September 11, 2024
Description: On September 11, 2024, progress was made with a core upgrade to the upcoming release, updating core dependencies for JavaScript and Rust, which enhances implementation speed for core protocol changes. Important business development calls were also held, leading to further steps in integration. Additionally, discussions on blockchain technology highlighted the unique aspects of decentralized systems compared to traditional databases, prompting considerations for applying these principles to address fragmentation and interoperability challenges in the Light project.

### Light Progress

Shipped a core upgrade to the upcoming release!

[#005 - Tokio Upgrade | Light Changelog](https://light.so/changelog/005)

Our core dependencies are now all updated (at least, for javascript and rust deps) to the latest possible dependencies in which now enables us to move at maximum speed. This is due to the fact that:

- Core protocol implementations often benefit from state of art downstream implementations, if not bottle necked like through [alloy](https://alloy.rs/), [foundry](https://getfoundry.sh/), and [viem](https://viem.sh/).
- Being able to update to the latest dependency enables us to implement [core protocol changes](https://github.com/ethereum/pm/issues/997) at lightning speed going forward.
- I like state of art tech 😄

Also had some important BD/Integration calls where some progress was made - excited for tomorrow as I continue to make progress for next steps! Proud that I was able to dish out couple of writings for a more concrete delivery during/after the meetings. I did miss out on one meeting though 😅

### Technical Readings

[Erigon Stage Sync and control flows](https://erigon.substack.com/p/erigon-stage-sync-and-control-flows)

Had a Chat w/ [Liam](https://x.com/liamzebedee) an he mentioned that “Blockchains are like DAGs, fundamentally. Especially POW chains”. If you think about it, this is very true - unlike traditional DBs, the state can diverge based on global consensus. This is what fundamentally sets crypto different.

https://x.com/liamzebedee/status/1833944903631643094

I wonder how I can apply this principal to Light though - this seems the best way to tackle some crucial aspects of dealing w/ fragmentation, interoperability and more so chain abstraction that Light is currently working on.

[Untitled](2024%2009%2011%20-%20Dependencies,%20dependencies,%20dependenc%20b9511cfea2bf437b91ab2808b40458c1/Untitled%20b2300c065bfa455db636fcf0447938ac.csv)
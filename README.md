# RailNext
 Let’s be real—estimating train arrival times in India right now is mostly luck. Apps like *Where Is My Train* are great for knowing where a train is *right now*, but they are strictly reactive. They just do basic distance-divided-by-speed math and assume clear tracks, completely blind to a goods train stalled or a red signal 50 km ahead that’s about to cause a two-hour delay.

That’s where **RailNext** comes in. Instead of just tracking current location, we use AI to actually *forecast* the delay before it happens. We map the entire rail network as a dynamic graph and feed live ISRO RTIS GPS data, signal aspect statuses, historical junction bottlenecks, and weather conditions into our ML model to predict accurate ETAs hours ahead of time.

European AI systems like in Switzerland (SBB) or Netherlands (NS) work great on their networks, but only because their tracks are hyper-disciplined and passenger-only. They struggle with Indian Railway real-world conditions. RailNext improves on these models by using Graph Neural Networks specifically tuned for our ground reality—mixed traffic (slow freight rakes sharing tracks with express trains), unreserved compartment boarding rushes, and heavy North Indian winter fog.

In short, RailNext gives passengers reliable ETAs on their phones and station displays, while equipping control rooms with predictive delay heatmaps to clear traffic bottlenecks before they turn into a mess.

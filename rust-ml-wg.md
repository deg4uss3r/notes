
# Rust Machine Learning Working Group

##  What value do you want to bring to the project?

The goal of this working group is to take inventory of the existing (and non-existing) machine learning (ML) libraries in Rust and improve or create any crates need to have a fully functional ML environment for Rustaceans. 

The working group would start off by taking stock of the current Rust environment for ML, create examples and test their correctness and usability of the crates that currently exist. 

After the initial pain point and requirements gathering, the working group would polish, improve, combine, and/or remove existing libraries to have a less confusing environment. 

The next phase would be to create any new crates or significantly change any existing crates for use to create ML or supporting frameworks (e.g.`numpy`/`pandas` full equivalents). 

## Why should it be put into place? 

Rust is a very good fit for ML developers, but might be very intensive to learn if they do not have a software engineering background to begin with. With the environment more mature Rust would have a significant speed advantage over Python and with the concurrency Rust offers would exceptional for parallel data processing for ML. As it currently stand there is not a lot of up-to-date tooling out there for ML in Rust. There exists crates, but a lot of them are fairly out-of-date and have not seen a commit in ~2 years. 

##  What is the working group about?

The working group is about polishing and getting ML libraries first class in Rust. This would include getting existing ML and supporting crates to "1.0" and developing any gap-filling crates that would need to be created in order to be usable by all ML research/developers (especially those who do not currently use or know Rust). The working group should also set guidelines for any future development in the ML sphere to adhere to (API consistency).

## What is the working group not about? 

This working group is not about teaching machine learning basics or taking ML/AI to the extreme beyond what currently exists in research. The working group would also not be about promoting anything created inside the working group *over* anything created outside the working group. We want a cohesive environment for ML in Rust and want those crates to be useable by everyone.

## Is your working group long-term or temporary? 

This working group would definitely be long-term.

### If it is temporary, when should it spin down?

N/A

## What is your long-term vision? 

The long-term vision for the Machine Learning Working Group would be to have a ergonomic environment for ML researchers/developers to use Rust for ML including new ML research that might not currently exist at the time. The APIs should be usable without the need for a deep knowledge of Rust. The environment should be very ergonomic to the point where it is easy to create new networks on any machine (GPU or GPU based). The group should take all considerations of a Pythonic-like environment as much as that make sense to do. It should be very easy to discover, understand, and evaluate any ML framework or supporting crates for researchers both experienced and new to Rust. 

I would love to see tutorials created in pure RustML especially standard ones like the datasets in MNIST.

## How do you expect the relationship to the project be?

I believe the MLWG would work closely with Rust project to create efficient algorithms in the lowest level possible with pure Rust. I also see this project working with the entire ML community in order to make sure we have the most up-to-date alogithms created at the time the working group is running. We should also interface with research to make sure we are easy to use for those who are deeply embedded into ML rather than software engineering so we are positive it is easy to use for all. 

## How do you want to establish accountability?

We will strictly adhere to the rust code-of-conduct and the leadership of this group is responsible to enforce it. The working group is open to everyone and we strongly believe in this. 

In terms of the WG accountability I would utilize a Github Pages for the WG to keep goals, timeline, and actions in sync with what the community thinks are important to further ML in Rust. Also including any other medium which is deemed fit by the Rust community and/or academia. 

## Which other WGs do you expect to have close contact with?

I expect to work closely with any other group contributing to algorithm-heavy parts of Rust development or any working group looking to create strong APIs into GPUs. Also, the core team, and possibly tooling groups. 

## What are your short-term goals?

The short term goals will be to take a close look at the current ML environment and formulate where needs the most ground work to start creating and adjusting APIs. Including taking suggestions from Rust developers/other working groups and machine learning researchers who do not currently use Rust for ML (rather Python or also importantly C++). 

## Who is the initial leadership?

I am happy to lead (i.e. mediate, coordinate, note-take, organize, etc.) the working group (I have a foot in both access to machine learning experts, and Rust language experts so more than happy to take the working group lead role). Heavy lifters would be a combination of ML researchers outside Rust as well as Rust developers in the irc `#rust-machine-learning` room and open to anyone else to join. 

## How do you intend to make your work accessible to outsiders?

I would plan to use the [arewelearningyet.com](arewelearningyet.com) site, as well as a separate Github Pages for the working group news, schedule, actions, and notifications. Twitter is also a powerful ally in posting small snippets of news. Youtube could also be used if the need for any video announcements arise.

## Everything that is already decided upon

IRC and Discord would/cloud be used, I would strongly prefer using only one chat medium and since Discord keeps chat history without significant development I would opt for that. However, are more than open to ideas/what the community thinks is best.

## Where do you need help?

Gaining attention to this working group and gather members to make ML awesome in Rust! Would be great to have an ML room on the Rust-lang discord server (I think one existed at some point but disappeared). 

## Preferred way of contact/discussion

Discord (and most things): deg4uss3r
Or here on internals 


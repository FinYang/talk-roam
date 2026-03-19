# `roam`: Remote Objects with Active-binding Magic


## DAD 26 Mar 2026

In R, data are most naturally distributed as objects bundled inside packages, but they comes with practical limits. Package size restriction of 5 MB make it difficult to include larger datasets, and updating data typically requires updating the entire package. 
The 'roam' package simplifies the creation of R objects that behave like regular data but are stored remotely and loaded when needed. This allows developers to work with larger datasets without inflating package size, while also enabling data to be updated independently of package releases. It also supports versioning, making it easier to manage and reproduce different versions of a dataset. 
In this talk, I will introduce the main idea behind 'roam', show how it can be used in practice, and briefly explain how it works behind the scenes.

## UserR! 2024

The "roam" package simplifies the creation of R objects that resemble regular objects but are sourced from remote locations. It empowers package developers to incorporate these "roaming" objects, which may surpass the 5MB limit, into their packages. Additionally, it facilitates dataset updates independent of package updates through functions that retrieve data from remote sources.
https://github.com/FinYang/roam

### Learning Outcomes
Attendees will gain an understanding of how the "roam" package facilitates package development in R by enabling the integration of standard-looking, remote-sourced objects exceeding the 5MB limit. They will learn how to leverage "roaming" objects in their own packages, enhancing functionality and scalability. Furthermore, attendees will discover the importance of separating dataset updates from package updates, and acquire practical knowledge on implementing data retrieval from remote sources for seamless dataset updates in their projects.

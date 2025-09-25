# List of Projects I Can Highlight

## Cubicdone
I made a [to-do list app](https://cubicdone.com) for myself because I was unsatisfied with the UX and functionality of other apps on the market.  
I also published it on [Product Hunt](https://www.producthunt.com/products/cubicdone). The launch didn’t go very well :)  
But my [YouTube video](https://youtu.be/mEKjFzGT8wc) about the launch got 43k views, and that’s when I started getting real users. In the end, though, most of them were just curious and didn’t actually stick with the product.  

Eventually, I didn’t see any conversions and ended up using it just for myself (as originally planned).  

The main challenge was local and remote database synchronization.  
I attempted a **local-first approach** so the app could be used offline without limitations. However, it didn’t go well because I spent 80% of development time on this feature and ended up not using it at all, so I cut it.  
Another challenge was integrating Clerk Auth with a Raycast extension — I failed to make it work, so I rewrote all authentication code to use **Lucia Auth** instead.  

**Technologies used:** Vue.js, Postgres, TRPC, Drizzle ORM, Lucia Auth  

- [Web app](https://app.cubicdone.com)  

<img width="2803" height="1243" alt="image" src="https://github.com/user-attachments/assets/d16d7923-7da0-4dd4-8636-975a8993557b" />

---

## Cooplay
[App](https://cooplay.app) for tracking the emotional state of a team, preventing burnouts, and improving overall team vibe. The app is being developed for the EU market.  
I was the **backend team lead**.  

The biggest challenge was developing algorithms responsible for calculating the overall mental health score of a team member and the whole team.  

**Technologies used:** FastAPI, Postgres, Flutter  

<img width="1132" height="864" alt="image" src="https://github.com/user-attachments/assets/90f1a8a2-d5ce-4181-a595-82d26b2db973" />

---

## Proximator
Developed while working at [Wildberries](https://wb.ru), the biggest marketplace in Russia.  

A microservice written in **Go**. Its purpose was to bypass bot protection of Wildberries’ main competitor, [ozon.ru](https://ozon.ru).  
It consistently handled over **10,000 RPS**.  

The main challenge was adjusting TLS settings (cipher suites) of requests and managing semaphores for each proxy so load balancing worked correctly with runtime configuration.  

**Technologies used:** Go, Prometheus, Grafana  

<img width="2405" height="1199" alt="image" src="https://github.com/user-attachments/assets/3c0085b9-cd7f-430c-a56b-eddc5cbbcfcf" />

---

## Procollab
The easiest way to describe it: a mix of **Product Hunt** & **LinkedIn** for college students.  
My role was **front-end tech lead**.  
Over **100,000 students from Russia** are registered on this service.  

The main challenge (non-technical) was communicating with non-technical “boomers” who owned the platform.  
From a purely technical perspective, the challenges were:  
- Managing Kubernetes-based CI/CD for both front-end & back-end teams  
- Making in-app real-time chat work reliably  

**Technologies used:** Angular, FastAPI, Postgres, Kubernetes  

- [Landing page](https://procollab.ru/)  
- [Web app](https://app.procollab.ru)  

<img width="2628" height="1218" alt="image" src="https://github.com/user-attachments/assets/01084096-15f5-4da2-8f17-8583a25d46a7" />

---

## Restless
An [HTTP framework](https://github.com/restless-rs/restless) for Rust inspired by Express.js.  
Our goal was to make it easy for Node.js backend developers to get familiar with Rust, so we wrote an almost exact clone of Express.js.  

The biggest challenge was **fighting the Rust compiler**. Rust’s super-strict type system didn’t allow the same tricks JavaScript does, which made development difficult.  

We got some downloads from the official Rust package manager ([crates.io](https://crates.io/crates/restless-web)), but eventually, the project didn’t gain traction and died.

**Technologies used:** purly Rust

<img width="1087" height="721" alt="image" src="https://github.com/user-attachments/assets/735b2b37-bbb5-4c0f-9f6d-6ba7fbe2efc3" />

## Honorable mention

Linear [Figma link](https://www.figma.com/design/jvQlj503T1CsqAyzpBLnH7/%D0%95%D0%B3%D0%BE%D1%80-%D0%A2%D0%BE%D0%BA%D0%B0%D1%80%D0%B5%D0%B2---%D0%9B%D0%B5%D0%BD%D0%B4%D0%B8%D0%BD%D0%B3--%D0%94%D0%B8%D0%B7%D0%B0%D0%B9%D0%BD-%D1%81%D0%B0%D0%B9%D1%82%D0%B0--Copy-?node-id=2986-115&t=Ko9ous54IT1HM10K-1)

Emap [Figma link](https://www.figma.com/design/UXOvm2zc1qILeGSgU1zVqL/%D0%9A%D0%BE%D1%80%D0%BF%D0%BE%D1%80%D0%B0%D1%82%D0%B8%D0%B2%D0%BD%D1%8B%D0%B9-%D1%81%D0%B0%D0%B9%D1%82_-%D0%94%D0%B8%D0%B7%D0%B0%D0%B9%D0%BD-%D1%81%D0%B0%D0%B9%D1%82%D0%B0--1.-%D0%92%D0%B2%D0%BE%D0%B4%D0%BD%D1%8B%D0%B5--2.-%D0%94%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B-?node-id=4820-348&t=cfqQ4kOHlBnW2car-1)

Armadion [Figma link](https://www.figma.com/design/BxRHAdlZIVBk9hoY4O03It/armadion?node-id=163-977&t=ToB3d431k2vMDEWK-1)

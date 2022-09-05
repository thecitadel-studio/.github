## A collective of individuals

Best engineers want freedom and flexibility. This is why it's becoming harder and harder to get them on board with permanent contracts. We've created a collective of impressive contributors met along the way, and we provide them with exciting projects to work on, so they stay around for the long run while keeping their freedom.‍ 

When an individual isn't enough, *Citadel* brings the organization of a team, so you keep the best of both worlds for your projects. We've built a productive remote culture enabling the ability to work instantly with anyone, from all over the world.

## Principles

A collective look very close to an agency. There are a few major differences, a collective is:

- **Horizontal**: There is no hierarchical level in a collective, but more different responsibilities (as described below);
- **Freedom friendly**: Each member can choose the missions, and the coworker of the collective to work with, with no obligations;
- **Transparent**: No hidden facts inside a collective, people work as equals and are aware of everything;
- **Flexible**: People can work in or out of the collective, it’s a bonus for members not a burden;

At Citadel we respect to simple rule before considering a business relationship with a client:

1. We sell only “from scratch” development services and maintenance of our own projects. This is to maintain very high-quality standards;
2. We only start a project if:
    - We have received and reviewed the final designs (UI and technical architecture);
    - We have the right team available;
    - The paperwork is complete;

# Retribution

### Daily rates

At The Citadel, daily rates are standardized among the collective. This is meant to be fair for everyone and ease the process of estimation for clients.

`code`: Push code to a repository

`review`: Do code review in a repository

`architect`: Has authority to determine a project architecture

`lead`: Has authority to resolve a squad organization and enforce rules among it

`admin`: Highest authority over a squad. Can challenge client wishes and planning, discuss technical specs, and plan directly with the client.

### The Lump-Sum framework (*forfait*)

**Lump-sum missions can only occur if *Citadel* has received a clear brief from the client. This kind of compensation system implies a short-term relationship with the client. Citadel prefers working with a pay-as-you-go framework, which better translates the willingness to settle a long-term and more flexible relationship.** This being said, in some situations, we may accept to work under lump-sum rules. The following explains how to handle the estimation.

Before a project starts, a `Staff` evaluates the amount of work required, this is meant to be with the squad, after reviewing the technical specs altogether. **The squad commits to respect the deadlines!** 

<aside>
💡 **About `variance` property**
As we only sell lump-sum services, there is a high risk of getting the estimation wrong. Having a wrong estimation can lead a squad to partially work for free. We need to mitigate the risk of underestimating a project. After the delivery, if a project has been over-estimated by more than 10%, we adapt the service fees to make them match the time actually spent. This way we don’t overcharge our clients.

</aside>

Once done, we apply the following formula:

- `numberOfDayEstimated` depends on the staff estimation (in accordance with the squad);
- `variance` is `3` (a standard ratio applied to mitigate our risk)
- `teamDailyRate` is the sum of the citadel rate of the squad (eg. a principal & a staff costs 660 + 720 = 1380)

```jsx
Math.round(numberOfDaysEstimated * variance * teamDailyRate) = totalPrice

/* 
// Eg. A project with a Staff, a Principal, and a Junior for 25 days estimated

numberOfDaysEstimated = 25;
variance = 3;
teamDailyRate = 495 + 660 + 770 (1925)

**numberOfDaysEstimated * variance * teamDailyRate = 144 375**
```

## How does Citadel earn money?

For each project, Citadel adds a €10,000 per month fee that includes:

- Full-time consulting service: technical architecture, strategy, meetings with founder, executives, and more generally the project management;
- Continuity insurance: Citadel guarantees the client that if a member leaves, the client still gets his team running as usual.

This fee helps Citadel to develop as a team and recruit people to get the collective organized at scale.

# Is AI a Heist on the European Economy?

AI summary: US companies are profiting significantly from AI services in Europe by bundling them with cloud infrastructure, leading to an outflow of resources and economic value. To counter this, Europe should create an open marketplace for AI infrastructure, ensuring transparency, competition, and maximizing returns on local resources.
Author: Max Schulze
Publication Status: Draft
Category: Policy Brief
Geographic Scope: International
Length: Brief
Policy Fields: Artificial Intelligence, Competition, Digital, Infrastructure
Programs: Sustainable Digital Products (https://www.notion.so/Sustainable-Digital-Products-d69c37fc786548099c2e92e4118ce905?pvs=21), Sustainable Digital Infrastructure Alliance (SDIA) (https://www.notion.so/Sustainable-Digital-Infrastructure-Alliance-SDIA-b8efc6f436e34de0938462f02490ee57?pvs=21)
Projects: NADIKI (https://www.notion.so/NADIKI-6b218ae29cb4442887dd2427acccefee?pvs=21)
Target Segments: Digital Policymakers (https://www.notion.so/Digital-Policymakers-46d6e91cd7fe4e9da883a3fe3478bd1f?pvs=21), Politicians who want to have a digital agenda (https://www.notion.so/Politicians-who-want-to-have-a-digital-agenda-157efc5c5853806ba811cd5ee031f72a?pvs=21)
Tags: artificial intelligence
Tags (website): Artificial Inteligence
Publish at Website: Yes

[Feedback](https://www.notion.so/Feedback-186efc5c585380a4807acf4d122daf77?pvs=21)

[Version 1](https://www.notion.so/Version-1-18fefc5c585380bd8a58efa182e0556e?pvs=21)

---

# Is AI a Heist on the European Economy?

Every year, US tech giants extract an estimated €19 billion from European economies through AI infrastructure - using European energy, land and resources while avoiding fair compensation. This invisible digital heist overshadows earlier concerns about AI's use of training data and intellectual property.

The mechanism is subtle but powerful: While providing valuable AI services to European businesses, US companies bundle these services with US-owned cloud infrastructure, creating a closed loop that captures value while bypassing European providers and tax systems.

Estimating the extracted value is hard, due to the lack of transparency and a strong practice of secrecy. However, taking a systems perspective can reveal the underlying extraction mechanisms and create a model to estimate the economic impact.

![*Overview of the systems-level view of money flow in AI services to infrastructure and resources. Source: Leitmotiv*](https://lex-img-p.s3.us-west-2.amazonaws.com/img/1935775e-88dd-4417-9e1a-f4120455b2d7-RackMultipart20250203-156-albvb3.png)

*Overview of the systems-level view of money flow in AI services to infrastructure and resources. Source: Leitmotiv*

1. **41.17% of European businesses with over 250 employees** [**use**](https://ec.europa.eu/eurostat/web/products-eurostat-news/w/ddn-20241205-1) **AI services.** Most services are delivered by US-based frontier model providers, which become deeply integrated into the European economy. Using survey data from [a16z](https://www.bain.com/insights/ais-trillion-dollar-opportunity-tech-report-2024/) on enterprise AI service spending, we estimate European enterprises spend 39 billion a year on AI services.
2. AI service companies spend about [**half**](https://www.bain.com/insights/ais-trillion-dollar-opportunity-tech-report-2024/) **of this revenue** on procuring infrastructure to deliver their services to European enterprises. This leads to **19 billion spent on cloud infrastructure**. US-based AI service providers **bundle their models** with US cloud infrastructure, like [Anthropic with Amazon Bedrock](https://www.anthropic.com/amazon-bedrock) and [GPT with Microsoft Azure](https://azure.microsoft.com/en-us/blog/introducing-gpt4-in-azure-openai-service/).
3. These US cloud providers use **European energy infrastructure, land, and natural resources** to [provide the infrastructure](https://www.datacenterdynamics.com/en/news/microsoft-to-invest-32bn-in-doubling-ai-infrastructure-and-cloud-capacity-in-germany/). However, the profits from providing the AI infrastructure and enabling the service delivery, which we estimate at 6.2 billion per year, are **not taxed** in Europe. European resources are utilized, but do not lead to direct value creation in the economy, creating an outflow of money and resources, an invisible digital heist.
4. The current shift, [exemplified by DeepSeek](https://edition.cnn.com/2025/01/28/business/deepseek-ai-nvidia-nightcap/index.html), from computing-intensive training to rather use more computing time to answer questions (inference) is further increasing the opportunity to act. The shift is leading toward even more foreign-owned cloud infrastructure in Europe, because inference needs to happen close to the customer. This is highlighted by the recent [news around DeepSeek](https://edition.cnn.com/2025/01/28/business/deepseek-ai-nvidia-nightcap/index.html), which used 10x less computing for training, but is using more computation for inference.

The missed opportunity for Europe is twofold. First, European infrastructure providers **are left out** of the 19 billion market for AI infrastructure. Second, the profits from the provisioning of infrastructure **are not taxed** which represents an estimated 1.34 billion (using the average EU corporate tax rate of 21.5%) in missed tax revenue. Given that energy infrastructure, land and natural resources are used, a return for society through taxation should be the minimum.

In this brief, we will explore the mechanisms of resource extraction, direct value creation as well as the market barriers which prevent European infrastructure providers from competing. Furthermore, we will give policy recommendations on how to separate the practice of bundling services and infrastructure and enforce transparency on the flow of infrastructure resources (digital resources) in order for Europe to regain control over its digital economy & infrastructure.

## How do enterprises import AI services that bundle the required computing infrastructure?

To understand the flow of money, we take a hypothetical example of a large European enterprise with an annual IT budget of 100 million euros. To illustrate our example, we assume 1% of the budget is spent on purchasing AI services. For our example, we assume the enterprise is buying services from a US frontier model provider (such as Anthropic, OpenAI, Google, xAI, and others). All of the service providers operate using a legal entity in the US. Consequently, the 1 million in AI service spent is flowing to the US and becomes an import for Europe.

To deliver the AI service, the provider must install its model on computers with the capability to run them and enable the model to be queried (inference). These computers contain Graphical Processing Units (GPUs) which provide the necessary horsepower to offer fast inference for the customer. All Frontier service providers rent those computers from US cloud providers, bundling their models with the computing resources of the infrastructure provider. The reverse also happens, where a cloud provider does the bundling. This is the case with Anthropic’s [Claude model](https://www.anthropic.com/amazon-bedrock), which is available within Amazon’s cloud platform as [Amazon Bedrock](https://www.aboutamazon.com/news/aws/amazon-bedrock-anthropic-ai-claude-3).

<aside>
⚡

This is akin to an electric car manufacturer partnering with a utility and offering a car that is bundled with an electricity contract of the utility, locking customers into a single utility providing the electricity.

</aside>

## Why are AI service providers not looking for cheaper suppliers and pursuing higher margins from bundling?

An obvious question that comes to mind is: If the cost of computing is bundled with the model to provide the service, wouldn’t the model provider have an incentive to partner with infrastructure providers who offer the lowest price for the compute? This would increase the profit margin of the model provider and thus would make economic sense.

There are two straightforward reasons why this doesn’t happen:

- As the bundling goes both ways, the model provider can tap into the vast pool of existing customers of the cloud infrastructure provider. In fact, as the case of Anthropic, 60-75% of its revenue [comes from](https://www.tanayj.com/p/openai-and-anthropic-revenue-breakdown) customers using the model through Amazon AWS. This means the infrastructure provider is **both a supplier and a sales channel** at the same time. If Anthropic were to choose another cloud supplier, it wouldn’t be unreasonable to assume that Amazon would in turn threaten them to stop offering their model through their cloud platform.
- Large global cloud providers are using their cash-generating abilities - both from their primary businesses (e.g. advertising, e-commerce and licensing) and their cloud business - to place large orders (bets) with chip manufacturers such as Nvidia, Broadcom or TSMC, choking off the supply chain for European cloud infrastructure providers, who can’t match the spending or borrowing capacity of the US counterparts. According to [Omdia](https://www.datacenterdynamics.com/en/news/microsoft-bought-twice-as-many-nvidia-hopper-gpus-as-other-big-tech-companies-report/), Microsoft alone ordered 485.000 Nvidia Hopper chips in 2024. Nvidia’s production capacity is [forecasted](https://finance.yahoo.com/news/nvidia-2025-gpu-unit-forecast-142417942.html?guccounter=1) to produce 3 million Hopper chips in 2025.

Looking at the price difference between digital resources sold by Amazon AWS and a European cloud infrastructure provider, OVH, we can see that the lock-in is strong enough to withstand the potential of higher margins for the AI service provider. In the below comparison, the products on offer are nearly identical, yet OVH’s monthly price is 38% lower on long-term contracts and 44% on a month-to-month basis.

One noteworthy difference is that OVH is not offering to fully absorb the capital costs when a customer won’t commit for at least 6 months. This adds a one-off setup fee, which together with the monthly costs, is still lower than AWS’s more flexible monthly price, but customers might perceive it as a barrier if they only want to use the digital resources for a few hours at a time. AWS offers greater flexibility at a high mark-up which it uses to absorb the potential financial risk of underutilized capital.

*Amazon AWS Product: g6e.12xlarge, 4 x NVIDIA L40S GPUs, 48 vCPU, 384 GB Memory*

*OVH Product: HGR-AI-2, 4 x NVIDIA L40S GPUs, 64 vCPU, 384 GB Memory*

| Contract Term | AWS Price USD/month | OVH Price USD/month |
| --- | --- | --- |
| Monthly/no commitment | 9.577,61 | 4.211,99 (monthly) + 3.317,99 (one-time installation costs) |
| 1 year contract | 6.033,90 | 3.790,73 |
| 2 year contract | not available | 3.579,86 |
| 3 year contract | 4.965,04 | not available |

<aside>
⚡

We have seen this before in the telecommunications sector when Apple released its first iPhone. These were "SIM-locked" to a single mobile network operator. Here again, both forces were at play. For Apple to deliver the iPhone product experience, it required a strong mobile network **and** a sales channel. The operators were cash-rich, offering the iPhones bundled with their infrastructure resources at no upfront cost for the customer. They also had the customers already, thus providing the sales channel which Apple needed. Even though Apple didn't benefit from the lock-in, most customers complained heavily; it provided Apple with a fast way to a) access a lot of customers and b) partner with networks that had the quality and scale required to maximize the iPhone user experience, which was highly affected by the quality of the internet speed available on the network.

The bundling practice is regulated through the EU Unfair Commercial Practices Directive (Directive 2005/29/EC of 2005) with each Member State having their own legislation on SIM-locking. It’s important to consider if the policy principles can be applied to AI service & infrastructure bundling.

</aside>

### Readily-Available Infrastructure, Customer Access and Equity Investment - The Perfect Lock-In?

Furthermore, it’s worth pointing out that most of the partnerships that we see in the market today are on the surface not exclusive; they are so in reality, unless the AI service providers can diversify their sales channels. As the example of Anthropic illustrates, if a company derives 60-75% of its revenue from a single partner, who is also the largest supplier, it creates dependence. This is paired with equity investments of the suppliers in the AI service providers (Anthropic/Google, OpenAI/Microsoft, Mistral/Microsoft) which creates further influence and constraints.

It’s a triple helix: The US cloud providers have the infrastructure with the required scale & technical capabilities, offer unlimited access to their global customer base and also invest equity providing the required capital for the loss-making businesses. How can an AI service provider choose not to work with a US cloud provider?

## Doesn’t Europe benefit from US cloud providers using data centers located on the continent?

US cloud providers own data centers in Europe. The data centers consume energy, create jobs and generate tax revenues from wages, property and corporate income tax. Or don’t they? And how much economic value-add does Europe capture from providing the socialized grid infrastructure, land and natural resources?

The short answer is: We don’t really know. Real data and scientific analysis are missing because the sector is wrapped in secrecy and schemes to obscure many of the aspects around energy and natural-resource use, job creation and taxes. Examples range from financial statements - Google doesn’t [disclose](https://www.sec.gov/Archives/edgar/data/1652044/000165204423000045/goog-20230331.htm) cloud infrastructure revenues per country but rather aggregated them Europe, Middle East and Africa (EMEA) to energy use - all cloud infrastructure providers only disclose the total capacity, not the actual energy use.

Taxation becomes even more complex, as the vertical integration of the companies causes confusion about which legal entity is generating revenue using which product or service. The [financial report](https://www.bundesanzeiger.de/pub/de/suchergebnis?14) of Microsoft’s German subsidiary mentions Azure, its cloud infrastructure service, 19 times but doesn’t contain any financial information on revenues or operational costs related to it. It shows revenues of 7.85 billion for the German market, 2.962 employees and taxes of 104.7 million. The financial report does not explain if these employees and revenues are made from Microsoft’s licensing business (for Windows, Office and other software licenses) or the selling of cloud infrastructure services. It mentions data centers, but its assets don’t show any. It describes itself as sales, marketing and customer support organization. How much taxes are paid on the profits generated from selling cloud infrastructure by the US conglomerates in Europe? We don’t know. What we do know is that the regions in which they set up their data centers [are glad](https://www.zdf.de/nachrichten/wirtschaft/rechenzentren-rhein-main-gebiet-fluch-segen-100.html) to receive the property and limited trade taxes, though these only represent a small fraction of the likely profits which we’ve calculated below.

Untangling the many business lines and legal structures of these conglomerates is not the aim of this brief - but rather to help to raise the questions that we must seek answers to. In the following part, we outline 3 key questions on the value-add from cloud & AI infrastructure to the European economy. In this brief, we focus on the value creation from digital infrastructure, putting potential productivity effects of digitalization and digital products & services aside. Each part of the digital realm should create added value for Europe and that starts with the infrastructure which is responsible for the majority of energy, land and natural resource consumption.

### Is the energy use by digital infrastructure adding value for Europe?

The assumption is that digital infrastructure, like other sectors, is purchasing energy from the European energy market, and thus adding value to overall system. Digital infrastructure represents an electrical baseload, meaning it requires power 365 days a year, offering little to no flexibility. Hence, in the new energy market of volatile renewable energy, it may not be desirable to add electrical baseloads of hundreds of megawatts to the system. At the least it will require investment in reinforcing grid infrastructure, of which the costs are socialized. So the first question that we must be able to answer is: What is the socialized cost of hosting hyperscale data centers in Europe?

In the same line, we must ask: How much added value do we generate from selling electricity to these data centers?

Most US cloud providers and real-estate trusts operating data centers in Europe [use](https://about.bnef.com/blog/corporate-clean-power-buying-grew-12-to-new-record-in-2023-according-to-bloombergnef/) Power Purchase Agreements (PPAs) to buy electricity directly from power plants. This is an increasingly [common practice](https://www.eurelectric.org/in-detail/ppas/) for large electricity consumers with the intention to provide long-term contracts to investors in renewable energy generation to reduce market risk. These contracts usually fix the price over long periods (15-30 years), shielding them from fluctuations in the energy market. The power plant receives long-term guaranteed income, though it might not benefit from increases in the power price over the next 15-30 years. The investors building the power plants reduce their risk but also forfeit potential value-creation opportunities. Many of them are financed by pension funds. For the digital infrastructure operators it’s a competitive advantage. They know they will continuously need more power, so they can never buy too much. It locks in prices over long periods providing a hedge against market fluctuations. And it’s a hedge that is not available to many competitors as PPA require significant amounts of capital or securities to sign long-term contracts.

According to [Bloomberg](https://about.bnef.com/blog/corporate-clean-power-buying-grew-12-to-new-record-in-2023-according-to-bloombergnef/), Amazon in 2023 announced 8.8GW of PPAs across 16 countries. The company’s clean energy portfolio totals 33.6GW, which is greater in size than the power generation fleets of markets like Belgium and Chile. To meet their (clean) energy target, they need to buy another 105GW, **or more than three more Belgiums** to cover their **current** power demand.

The PPAs are designed to stimulate the investment into more renewable energy production. For the cloud infrastructure providers, the main objective is to have a long-term hedge on the power price, as it represents the main operating cost for them. What’s even better: PPAs also provide lower-cost electricity and faster access to more of it, as RE systems can be built comparatively quickly and produce power at lower costs than fossil fuel-based power plants. This becomes apparent as availability of power has become a constraint, which is pushing many infrastructure providers to use gas turbines in the United States and [Ireland](https://www.friendsoftheearth.ie/publications/data-centrres-and-the-carbon-budgets-prof-hannah-daly-dec-20/). This means that availability, not price, is the deciding factor (and apparently not emissions).

This is demonstrated in Ireland through a [study](https://www.friendsoftheearth.ie/publications/data-centrres-and-the-carbon-budgets-prof-hannah-daly-dec-20/) by Professor Hannah Daly of UCC commissioned by Friends of the Earth. Daly shows that between 2017 and 2023, all additional wind energy generation was absorbed by data centers. According to the research, dozens of data centres either have or are seeking connections to the natural gas network.

Coming back to our question on the economic value-add, we must examine the real effects of expanding digital infrastructure:

- When digital infrastructure operators use PPAs, they stimulate renewable energy investment. These investments cover mostly additional power demand that they create. Covering their electrical baseload requires investments in grid reinforcement and support from fossil-fuel power plants, which creates emissions. What are the benefits from this development for Europe?
- If US cloud providers use their financial size to continuously develop new power plants for themselves while the overall European energy system is facing constraints - how do we ensure competition from European actors who might not be able to sign long-term PPAs and thus are left out?
- Even with expanding power generation through PPAs, the energy for the US-owned digital infrastructure travels through the grid, for which the costs are socialized. This grid is facing congestion and bringing the energy to the data centers is increasingly becoming a headache for European power grids and require significant investments. What is our return on investment for reinforcing our grids to serve these digital resource factories? And does the congestion lead to missed opportunities for small- and medium-sized European digital infrastructure providers who can’t get any power at all?

### How many jobs & taxes does the development of digital infrastructure in Europe add to our economy?

There are few sectors that talk as much about spill-over effects as the digital one. Of course, digitalization can increase productivity and the digital economy can create new growth opportunities across all other industries and sectors. But what about the sector’s direct value-add to the economy? To paraphrase from a [recent report](https://international.eco.de/spillover-effects-of-data-centres-the-backbone-of-the-ai-revolution-in-germany/) of a German industry association representing digital infrastructure operators on spill-over effects: *5.9 million employees depend on the cloud (…) -* sounds great, but how many employees **can** **depend on employment** from the cloud’s infrastructure in Europe?

Two ways to create impact on local economies where data centers are built is through employing local labor, payroll taxes and property taxes. We will use an example based on data from a [study](https://copenhageneconomics.com/wp-content/uploads/2021/12/copenhagen-economics-hyperscale-data-centres-and-related-infrastructures-the-case-of-finland_november2020.pdf) commissioned by Google for their cloud infrastructure in Finland.

<aside>
⚡

Missing from the report are, as is often the case, the actual megawatts (MW) of data center capacity built by Google in Finland, though we can imply that the 445 MW in PPA purchases mentioned in the study should be roughly the power capacity of the data centers in Finland.

Furthermore, the report blends indirect and direct job creation together and, through annual averages, includes the labor-intensive construction period in its calculations.

</aside>

We are going to use only the direct jobs created for the actual operation of data centers (annual average of 220 staff between 2007-2020, according to the study).

From this (limited) data, we can first establish an estimate of the payroll tax and social contributions for Google in Finland. We are generous and assume staff on average is earning 88,200 per year. Social contributions amounting to 25% of the income will be around 22,050 per year. Income taxes will be about 23,142. For 220 staff, this results in:

- 4.85 million in social contributions
- 5.09 million in income tax
- 14.31 million in wages
- Total: 24.25 million

It is important to note that Google is likely paying property taxes for the facilities, though in the absence of information on the exact size and applicable tax rate, it is difficult to provide an estimate. These calculations are further validated by a report by the [US Chamber of Commerce from 2017](https://www.uschamber.com/assets/archived/images/ctec_datacenterrpt_lowres.pdf), which showed that large data centers support about 157 local jobs receiving an estimated $7.8 million in wages and paying $1.1 million in state and local taxes. To compare European cloud & data center providers, we have looked at the public financial & employment records of US real-estate funds who operate data centers on behalf of cloud providers and compared them to German competitors. On average, US firms create 3 operational jobs per megawatt of data center capacity vs. an average of 9 operational jobs for the German providers ([study by the German Ministry of Economic Affairs](https://www.bmwk.de/Redaktion/DE/Publikationen/Technologie/stand-und-entwicklung-des-rechenzentrumsstandorts-deutschland.pdf?__blob=publicationFile&v=10)).

To help put this into perspective, we made an estimation for how many digital resources can be produced using the 445 MW of facilities located in Finland. It’s an attempt to get an answer to the question: How much taxable profit does Google’s cloud infrastructure generate using the data centers in Finland but which financially accounted for in the US?

<aside>
⚡

For the scope of this analysis, we assume that the entire data center is used for AI Inference, meaning the delivery of AI models as a service. Cloud infrastructure in reality provides many services, though from our previous work we know that the economics for AI infrastructure and traditional cloud services are not as different, AI infrastructure requires more upfront capital investment, the business model of selling time-shares and futures in cloud infrastructure remains the same.

</aside>

- For our example, we assume Google spends about $1 billion (840 million) in AI infrastructure equipment (machinery).
- We assume they can secure enough customer demand to operate the machinery at an average 45% utilization over a year.
- With this infrastructure, they are able to generate an estimated $517 million (€434 million) in revenue per year, or about $3.1 billion (€2.6 billion) over the lifetime of the machinery (estimated at 6 years).
- If utilization scales up to 65%, revenue swells to $795 million (€668 million) per year, while retaining the same staff costs to operate the facilities.
- Google [reports](https://www.cnbc.com/2024/10/31/amazons-cloud-unit-records-highest-profit-margin-in-at-least-a-decade.html) one of the thinnest operating margins, 17%, of the 3 major players which results in operative earnings of an estimated $88 million for our example. If we take the average operating margin of the 3 leading cloud infrastructure providers, which is 32%, the result would be $163 million. If the utilization rises to 65%, the results are $116 million and $216 million respectively.
- Over the lifetime of the facility (15 years) at an average utilization of 45%, the total profit can be estimated at $1.31 billion.

This means that over the lifetime of the facility, Finland’s infrastructure and resources are supporting $1.31 billion of value creation for which it receives property taxes and wage taxes but no direct tax income from the profit itself. Does this represent an adequate return on infrastructure and resources for society?

In the US, many states are competing for data centers to be located in their jurisdictions, often by giving [hefty discounts](https://www.notion.so/Is-AI-a-Heist-on-the-European-Economy-184efc5c5853808eb409d856df54a32c?pvs=21) on property and sales tax. This is the result of [persistent lobbying efforts](https://www.fierce-network.com/security/why-are-us-taxpayers-subsidizing-cloud-boom) and encouraging competition among states by the US cloud providers themselves. This raises another question, are European regions already doing the same?

<aside>
⚡

You can [download the model](https://notion.leitmotiv.work/AI-Inference-Infrastructure-184efc5c585380419aa6cd483b33dc41?pvs=4) we used for our calculations, including all the sources we used here. We believe in transparency.

</aside>

## Europe hasn’t missed the opportunity to capture economic value from AI yet, but we must act now.

While Europe might feel it's falling behind on the training of new AI models, it still has a window of opportunity to participate in the value creation from delivering these models on its own infrastructure. This requires swift policy and regulatory intervention to open the digital and cloud infrastructure market, enabling European digital infrastructure providers to participate, compete, and capture part of the value creation of AI for Europe and its member states.

The competition on AI model development between China and the United States is already leading to model training requiring less computation, as shown with the recent release of [DeepSeek](https://www.nytimes.com/2025/01/27/business/dealbook/deepseek-tech-stocks-reckoning.html). Therefore, subsidizing the development of dedicated AI model factories is likely going to be short-sighted and the recent announcement Stargate, a $500 billion project for an AI training facility, should not be given much attention. DeepSeek was trained with 10 times less GPUs than OpenAI’s recent o1 reasoning model. If this efficiency gain in training can be accomplished in a year, it’s likely it will further spiral downward, making a gigantic training facility obsolete. Furthermore, through the proposed marketplace in our policy recommendations, Europe could build its own gigantic AI factory through aggregation and decentralized computing, delivering training at much lower energy costs and without the delay of constructing hundreds of megawatt of data center facilities. **European collaboration is the key.**

Most importantly, the recent release of reasoning models (chain of thought, such as GPT-o3 and Gemini Flash) the demand for computing is **shifting even more towards inference** rather than training. The increased use of inference will drastically increase the digital resource demand within Europe due to the fact that the inference needs to happen close to the user. This further amplifies the opportunity to regulate and open the market for European actors to participate in the delivery of digital resources for AI inference - irrespective of the AI model used. The growing demand for inference computing will lead to increased revenue from digital resources within Europe's geographic boundaries and market liberalization can enable European actors to participate.

## The Path Forward: Breaking the Infrastructure Lock-In

Our analysis has revealed three critical challenges that must be addressed:

1. **Value Extraction Without Return**: US tech companies are using European resources (energy, land, infrastructure) while structuring their operations to minimize their tax obligations and economic contribution. The estimated €19 billion in infrastructure spending generates minimal local employment and tax revenue compared to European providers.
2. **Bundling Creates Market Barriers**: The practice of bundling AI services with specific cloud infrastructure providers creates an artificial barrier to competition. European infrastructure providers, despite often offering better prices, cannot compete effectively because they lack access to both the AI service partnerships and the massive capital needed to build ahead of demand.
3. **Resource Control Through Scale**: US cloud providers use their enormous cash flows from other businesses to lock up critical resources - from energy contracts to GPU supplies - creating a self-reinforcing cycle that makes it increasingly difficult for European competitors to enter the market.

These challenges are systemic and interconnected. They cannot be solved through traditional competition policy alone. Instead, Europe needs a coordinated approach that creates new market structures while ensuring fair compensation for European resources. The following policy recommendations outline how this can be achieved.

## Policy recommendations

### 1 - EU Single Market: Force foreign AI providers to use European marketplace to purchase computing, digital resources

A marketplace for digital resources would function similarly to modern energy markets, creating unprecedented transparency into both resource flows and value creation. Every transaction would be logged - from the purchase of digital resources to the actual utilization of infrastructure - providing clear visibility into how AI services consume European resources.

This data enables policymakers to track key metrics like the geographic distribution of infrastructure usage, energy consumption patterns, and most importantly, the flow of money between service providers, infrastructure operators, and end users. For example, when a French company uses an AI service, the marketplace would show exactly which infrastructure provider delivered the computing power, where that infrastructure is located, how much energy it consumed, and what portion of the service fee went to infrastructure versus the AI model provider. This granular transparency is essential for ensuring fair competition, appropriate taxation, and understanding the true economic impact of AI services in Europe.

This requires:

- Any AI model service provider selling products in the European Single Market to European companies must purchase digital resources from an open marketplace.
- Providers offering products such as chat or technical interfaces must be unbundled in the Single Market and cannot be offered as a combined infrastructure and service product.
- Providers must give customers transparency about which digital resources were bought through the market to provide the service (at least geographic location, name of the provider, and ideally also environmental impact or energy source)
- Providers must offer customers the ability to set boundaries for what kind of digital resources should be used to provide the service (e.g., choose a geographic boundary, a selection of acceptable energy sources, or required security certifications)
- Providers should provide invoices in which the service fee (for using the AI model service) and the digital resource costs (infrastructure) are separated.

### 2 - Create an open market for AI infrastructure within Europe

Europe should create an open marketplace for buying and selling digital resources, specifically for AI infrastructure. This market should be an independent, public, not-for-profit entity financed through transaction fees and with a clear statutory mandate, transparency, and limited leadership terms. This entity is the market operator providing an exchange for digital resources required by AI model providers, either for training or service delivery. On the supply side, it enables providers to sell their AI infrastructure capacity into a market as a standardized product, receiving price signals to gauge demand and support investment decisions.

Most importantly, this market creates competition on price, a dimension with which many European digital infrastructure providers already outperform the US cloud infrastructure providers. Where European providers cannot compete are the following areas, which are addressed by the market:

- **Scale:** As they lack the large cash flows that the vertical integration of Google, Amazon, and Microsoft's infrastructure brings (advertising, e-commerce, and licensing), European providers cannot afford to overbuild capacity but must grow organically with demand. This leads to a "landgrab" of resources, land, energy, GPU chips, and other resources by the large cloud providers, knowing that their bundling practices will utilize these resources eventually.

To give a sense of scale: Microsoft's free cash flow in 2024 [was](https://www.macrotrends.net/stocks/charts/MSFT/microsoft/free-cash-flow#google_vignette) $70 billion. In comparison, OVHcloud, one of the largest cloud providers in Europe, [reported](https://corporate.ovhcloud.com/en/newsroom/news/financial-results-h1-2024/) €477 million in cash and cash equivalents available in 2025.

- **Distribution:** The US cloud providers have "locked down" many of the distribution channels both in the direction of the AI model providers and toward the customers by paying significant kickbacks to managed service providers such as Capgemini, Accenture, and others. These kickbacks are priced in, leading to higher prices for enterprises.

An open market would solve the scale issue by providing aggregation of resources on a European level, akin to the European energy market. Every producer of digital resources could sell them into the market, and buyers would have a unified interface through which they could procure resources at scale (which may span tens or hundreds of providers across Europe). This would lead to higher efficiency, with the price signals of the market giving clear indication for providers when to run their facilities, when to expand, or when to scale down all effects already observed in the energy market.

The distribution challenge requires policy intervention to either force the distributors of enterprise AI services to utilize the marketplace in provisioning their products (e.g. through the procurement side) or by offering an alternative incentive to distribute only AI services using digital resources from the market to replace the kickback incentive.

### 3 - Facilitate Access to Critical AI Infrastructure and Equipment by Aggregating Purchasing on an EU Level

As we have shown, the stranglehold on the supply chain, namely on GPUs and other AI-related equipment by the global cloud providers, poses another challenge to developing a strong European market for digital resources of AI services.

Since most suppliers are private companies, this challenge should be overcome by aggregating demand in Europe. The blueprint is the procurement of vaccines during the COVID-19 pandemic. The EU aggregates the demand of the member states to place a much larger order than any single country would be able to.

In the case of AI equipment, the EU should not be the buyer. Rather, it should facilitate a coalition of enterprises, digital infrastructure providers, and others who require AI infrastructure or would like to use it from a marketplace to aggregate their purchase orders toward suppliers, creating an order that equals the size of the existing cloud infrastructure providers.

Similar to CoreWeave, where Blackstone and Magnetar [provided](https://www.prnewswire.com/news-releases/coreweave-secures-7-5-billion-debt-financing-facility-led-by-blackstone-and-magnetar-302148876.html) debt facilities to place orders worth $7.5 billion (€6.3 billion), the EU and its member states can consider providing guarantees to the purchase group to secure debt financing that would otherwise not be accessible to smaller and medium-sized providers.

## Outcomes

- **Jobs:** European providers have the majority of their staff within the EU, especially highly skilled labor, and are growing staff at their headquarters. Our analysis for the German Ministry of Economic Affairs showed that on a data center facility level, regional and national actors create three times more jobs than facilities owned by major US cloud providers. Additionally, the majority of employment created from cloud infrastructure is in software and infrastructure engineering roles, which the majority of EU providers employ within EU member states.
- **Efficiency and Costs:** Establishing an open marketplace will lead to price signals and transparency, increased competition, and efficiency, thus reducing costs for AI infrastructure and digital resources. These cost reductions underpin the competitiveness of AI models and services made in Europe and lead to non-EU AI companies seeking access to the market for their services.
- **Better Competition:** Current competition in the cloud and digital infrastructure market is broken because Europe lacks the equivalent, vertically integrated, cash-generating digital product companies of the US by allowing them to fully integrate each part of the value creation chain. Building cloud infrastructure has displaced most of other cash-generating processes of these companies and therefore this is where they gain their power.

**By establishing an open market, Europe creates a new, level playing field in which they and EU providers can compete on price and not market access or distribution, which are locked down.**

- **Maximize the Return on Energy and Resources for European Society:** A marketplace does not just serve competition and efficiency; it also creates transparency on the flow of digital resources, pricing, and actual demand and supply. It also offers a path to taxation and levers to maximize the return for European society on the land, energy, and natural resources that we collectively spend on AI infrastructure.
- **Transparency for Further Regulation, Sustainability, and Energy Management:** With a transparent market, trade flows, environmental impact, and use of energy become visible and accessible while further driving fact-based policymaking that will shape a competitive, sustainable, and open market embodying European values.
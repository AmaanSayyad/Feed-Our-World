# FOW (Feed Our World)

# 👨‍🌾 Introduction
Introducing FOW-FARM: A mobile-based website leveraging CELO blockchain to revolutionize the food industry. We connect producers and consumers directly, reducing food waste and eliminating unnecessary transaction fees. With our user-friendly platform, producers can showcase their products while consumers enjoy secure and cost-effective transactions. CELO blockchain ensures scalability and efficiency, transforming traditional supply chains. Say goodbye to credit card fees as FOW-FARM enables direct peer-to-peer transactions, empowering both producers and consumers. Join us in creating a sustainable future, where connectivity and blockchain technology drive a more efficient and transparent food industry. Together, we can make a significant impact on reducing waste and fostering a healthier planet.

# 🌽 Why FOW-FARM ?
FOW-FARM: Connect producers, consumers, and cut food waste. Our mobile site, powered by CELO blockchain, eliminates transaction fees. Showcasing products, secure transactions, and sustainability. Join us for a transparent, efficient food industry that saves costs and reduces waste. Together, let's make a difference.

Key Benefits and Use Cases:

- Efficient Food Distribution: The application streamlines the food distribution process, making it faster and more effective. Food suppliers can directly connect with non-profit organizations, avoiding delays and reducing food waste.

- Transparent Tracking: Blockchain technology enables transparent and immutable records of all food donations. Users can track the journey of food from the point of donation to the point of distribution, ensuring fairness and accountability.

- Disaster Relief: In emergency situations like natural disasters, wars, and pandemics, the application provides a robust and agile system to quickly distribute food to affected communities, aiding in disaster relief efforts.

- Reduced Food Waste: By connecting surplus food with those in need, the application helps reduce food waste, promoting responsible consumption and production.

- Customizable Donations: Users can choose specific food items, considering dietary preferences and cultural needs, making the donation process more personalized and relevant.

- Empowering NGOs: Non-profit organizations can better plan and optimize their resources, ensuring that food reaches those who need it the most.

- Privacy and Security: The application ensures the privacy and security of user data, assuring users that their personal information and donations are protected

## What it does
Feed Our World is a decentralized blockchain and Dapp-based solution that connects producers and consumers through an on-demand system. By streamlining the food acquisition process, reducing middlemen, and using blockchain technology to track food more efficiently, Feed Our World aims to put control of the food chain into the people’s hands, creating an On-Demand system and ushering in an era of food prosperity for all.

Our project's primary objectives include:

1. **Streamlining Food Donation:** Simplify and expedite the food donation process for both donors and recipients.

2. **Ensuring Transparency:** Utilize celo blockchain technology to create a transparent and immutable ledger of all food donations.

3. **Promoting Community Engagement:** Encourage community involvement by allowing individuals and organizations to respond to hunger relief requests in real-time.

4. **Reducing Food Waste:** Connect surplus food with those in need, minimizing food wastage.

# 🥑 UI / UX
<p style="display: flex; justify-content: space-between;">
 <img src="./img/Frame 1.png" width="100%" />
</p>

## How It Works

**Feed Our World** operates through the following key steps:

1. **Request Generation:** Individuals create food donation requests by capturing a photo of the needy's situation and sharing their location through the mobile application.

2. **Blockchain Recording:** Each request is recorded on the blockchain for transparency and traceability.

3. **Donor Engagement:** Donors, including travelers, NGOs, restaurants, and individuals, can review requests and provide food donations.

4. **Traceable Distribution:** The entire process is traceable on the celo blockchain, ensuring food reaches its intended recipients efficiently and accountably.

## How we built it
We built it using HTML, CSS, TypeScript, Solidity and Celo Blockchain. Feed Our World allows donors to track their donations and ensure that their contributions are being used for the intended purposes. The platform also enables transparency and accountability by leveraging the power of the Celo blockchain to record all transactions and donations securely.

## Challenges we ran into
During the development of Feed Our World project, encountered a significant challenge related to optimizing transaction costs on the blockchain. Aimed to ensure a seamless and cost-effective user experience, reducing gas fees for transactions became crucial.

Overcoming the Challenge

To address this hurdle, conducted a thorough analysis of the smart contracts, focusing on the areas that consumed the most gas. Identified gas-intensive operations and explored alternative ways to reduce gas consumption while preserving functionality and security.

- Optimizing Smart Contracts: Applied gas-saving techniques such as using storage variables efficiently, minimizing redundant calculations, and avoiding loops that could lead to high gas usage.

- Batch Processing: For certain operations, Implemented batch processing, consolidating multiple transactions into a single batch to reduce the overall gas cost.

- Off-Chain Data Storage: Decided to store non-critical data, such as user profiles and preferences, off-chain. This approach lessened the burden on the blockchain and led to cost savings.

- Gas Estimation Tools: Integrated gas estimation tools into the frontend, providing users with real-time estimates of gas fees before confirming transactions. This enhanced transparency and allowed users to make informed decisions.

Overcoming this challenge has not only improved the user experience but also contributed to the platform's scalability and adoption potential. Remain committed to continually refining and enhancing the solution to make a positive impact on hunger relief efforts worldwide.

## What's next for Feed Our World
“No person will sleep with an empty Stomach”, is the main motto of the proposed application. 
Severing the hunger of the needy people and controlling the waste of food is the main concern. 
The team plans to continue developing the platform and expand its reach. We aim to partner with more charities and organizations to make the platform even more impactful. We also plan to add more features and capabilities to the platform to make it even more user-friendly and efficient.

# 👇 Prerequisites

Before installation, please make sure you have already installed the following tools:

- [Git](https://git-scm.com/downloads)
- [NodeJs](https://nodejs.org/en/download/)


# 🛠️ Local development
For local development do following...

```sh
  git clone https://github.com/AmaanSayyad/Feed-Our-World.git
  cd FOW-FARM/client
  npm install
```
then create a `.env` file and paste from `env.txt` file inside `client` folder. Fill all those empty project Id's and API key's and then run,

```sh
  yarn dev
```

# 👨‍💻 Contributing

- Contributions make the open source community such an amazing place to learn, inspire, and create.
- Any contributions you make are **greatly appreciated**.
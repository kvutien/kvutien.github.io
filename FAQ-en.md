# Machu Picchu's Frequently Asked Questions
_version of July 4th, 2021_
## Is Machu Picchu about SSI, Self-Sovereign Identity?
No. Machu Picchu is not about identity.

What Machu Picchu wants to do at the first place is to make a kind of _LinkedIn_ where people-in-need post their data (whatever they want) with the help of their sponsor (chief of community or helper NGO field representative). These data are available to all organizations that offer services to these persons, to optimize these services.
It's Data as a Public Service. Identity is not of primary concern in this use case. 

The data is on IPFS, not on blockchain. They own this data and can revoke it because it's cryptographically signed by their cellular. 

GDPR wise, they are the Data Controller of their data.

## Is Machu Picchu about "banking the unbanked"?
No. Machu Picchu is not a bank, nor a banking tool. It is nonetheless "inclusive finance".

Once the objective explained above are achieved, Machu Picchu paves the way for more decentralised applications. We keep in mind that the purpose of Machu Picchu is NOT to replace the existing institutions, like banks, micro-finance, micro-insurance, administrations. It is to leverage low operative costs of state-of-the-art solutions to serve the lowest segments of market where the existing financial tools failed, due to their high costs.

## Is Machu Picchu another cryptocurrency?
No. Machu Picchu is not another cryptocurrency.

_To be explained_
## How can a person-in-need, who has barely a cellular phone, use the blockchain?
These people will access the blockchain through their chief of village, or equivalent, who has a blockchain enabled smartphone or tablet. This is a multisignature schema that has been prototyped by Machu Picchu in one prize-winning hackathon. The cellular sends via SMS an information to populate the profile. The originator of this SMS will be confirmed by the chief of village on his or her smartphone or tablet. The transaction will be sent to IPFS for storage. Depending on the information, a trace may be stored or not on blockchain.

Once the habit of doing so is acquired, this multisignature can be extended to many other community usages: participation to common chores, incentive for good practice, gender equality, education, decentralised exchange of tokens etc.
## What kind of data do you expect these people to post?
Anything they want, or actually everything their sponsors advise them to post.

In field reality, the people-in-need have no autonomy and they don't care about GDPR and the equivalent. They trust their sponsors, be it the chief of village or the NGO field workers.
Typically they would post the GPS location of their field or their refugees camp, what they grow, when they sow, when they harvest, the size of their family, their financial needs. There is no immutability, they can hide, change and delete. But the data is signed by them and confirmed by their sponsors that it comes from their cellular.
 
Technically, modern databases don't care about data models. The CPU have enough power to traverse all the data very quickly. Data is stored as key-value pairs. See [MongoDB](https://www.mongodb.com/what-is-mongodb) for example.
## How would you take care of the credibility of the data posted by persons-in-need?
The data are cryptographically signed by the owner. The sponsor also signs to confirm that the data comes indeed from the cellular of these persons. The sponsor doesn't even need to know the data to approve (zero-knowledge proof can be applied, although sparingly because it's expensive). In general, as for centuries in traditional villages, the data of each person is known by the whole community.

Later (much later), we could implement a kind of "like" by the other members of community to cross validate the data. It could be used to value the "price" in token that the data is paid by the users of the data. But it's very far fetched at this point in time.
## What is the business model? who pays?
Machu Picchu's purpose is to provide low cost tools for low income persons in low profile applications, but this doesn't mean that its solvable market is small.

The FAO estimated in 2013 that there are more than 500 million households in need. In 2019 the [Cash & Voucher Assistance programs totalled worldwide USD 5.6 billions](https://reliefweb.int/sites/reliefweb.int/files/resources/SOWC2020-Executive-Summary.pdf&usg=AOvVaw0ZepAEO1c1PBT_nhM9fmdz). This amount makes for only 17.9% of the total international humanitarian assistance, that can be potentially covered also with Machu Picchu. 

Despite this huge amount, it means only USD 11 per household per year currently . At such a small amount, banks lose money, donors lose money, helper organisations lose money and the persons-in-need are not well served.

Any percentage gained in operating costs translates into hundreds of millions more that can be shared between Machu Picchu and the persons-in-need.

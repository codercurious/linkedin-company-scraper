Scrape linkedin companies and extract complete information in bulk

## Features

**Data Export and Integration:** Once the scraping process is complete, you can easily export the extracted data in various formats such as JSON, CSV, or Excel. You can select fields you want. This allows for seamless integration with other tools and platforms for further analysis and utilization.

**Automatic Retry and Error Handling:** In case of temporary issues like network failures or timeouts, the actor has built-in automatic retry functionality. It intelligently handles errors to ensure a smooth and uninterrupted scraping experience.

**Ability to resume last failed runs**: In case of unexpected errors, you can simply go to actor's last run page, and click on 'Resurrect' button to resume last scraping progress

## Getting Started

Install [EditThisCookie](https://chrome.google.com/webstore/detail/editthiscookie/fngmhnnpilhplaeedifhccceomclgfbg) chrome extension 

Login to your linkedin account

Click on the extension and export the linkedin cookies

Paste the cookies into this actor's `Linkedin cookie` input field

✳️ **You might be interested in:**  [Crunchbase scraper](https://apify.com/curious_coder/crunchbase-scraper) | [Clutch companies scraper](https://apify.com/curious_coder/clutch-scraper) | [Linkedin reactions scraper](https://apify.com/curious_coder/linkedin-post-reactions-scraper) | [Linkedin post scraper](https://apify.com/curious_coder/linkedin-post-search-scraper) | [Other useful scrapers](https://apify.com/curious_coder)

Here is the sample output of this actor:

```json
{
	"name": "Microsoft",
	"description": "Every company has a mission. What's ours? To empower every person and every organization to achieve more. We believe technology can and should be a force for good and that meaningful innovation contributes to a brighter world in the future and today. Our culture doesn’t just encourage curiosity; it embraces it. Each day we make progress together by showing up as our authentic selves. We show up with a learn-it-all mentality. We show up cheering on others, knowing their success doesn't diminish our own. We show up every day open to learning our own biases, changing our behavior, and inviting in differences. When we show up, we achieve more together. \n\nMicrosoft operates in 190 countries and is made up of more than 220,000 passionate employees worldwide.",
	"websiteUrl": "https://news.microsoft.com/",
	"employeeCount": 227126,
	"specialities": [
		"Business Software",
		"Developer Tools",
		"Home & Educational Software",
		"Tablets",
		"Search",
		"Advertising",
		"Servers",
		"Windows Operating System",
		"Windows Applications & Platforms",
		"Smartphones",
		"Cloud Computing",
		"Quantum Computing",
		"Future of Work",
		"Productivity",
		"AI",
		"Artificial Intelligence",
		"Machine Learning",
		"Laptops",
		"Mixed Reality",
		"Virtual Reality",
		"Gaming",
		"Developers",
		"IT Professional"
	],
	"active": true,
	"crunchbaseFundingData": {
		"numberOfFundingRounds": 2,
		"lastFundingRound": {
			"localizedFundingType": "Post IPO equity",
			"leadInvestors": [],
			"fundingRoundUrl": "https://www.crunchbase.com/funding_round/microsoft-post-ipo-equity--4404bead?utm_source=linkedin&utm_medium=referral&utm_campaign=linkedin_companies&utm_content=last_funding",
			"announcedOn": {
				"month": 12,
				"day": 9,
				"year": 2022
			},
			"numberOfOtherInvestors": 1,
			"investorsUrl": "https://www.crunchbase.com/funding_round/microsoft-post-ipo-equity--4404bead?utm_source=linkedin&utm_medium=referral&utm_campaign=linkedin_companies&utm_content=all_investors"
		},
		"organizationUrl": "https://www.crunchbase.com/organization/microsoft?utm_source=linkedin&utm_medium=referral&utm_campaign=linkedin_companies&utm_content=profile_cta",
		"fundingRoundsUrl": "https://www.crunchbase.com/organization/microsoft/funding_rounds/funding_rounds_list?utm_source=linkedin&utm_medium=referral&utm_campaign=linkedin_companies&utm_content=all_fundings",
		"updatedAt": 1686770902
	},
	"adsRule": "REDUCED",
	"pageType": "COMPANY",
	"logoUrl": "https://media.licdn.com/dms/image/C560BAQE88xCsONDULQ/company-logo_200_200/0/1618231291419?e=1696464000&v=beta&t=tJOTOgUZntTPw0t4JQ4zFnc5G_D7GoOo0bIMjfKF5JE",
	"headquarter": {
		"country": "US",
		"geographicArea": "Washington",
		"city": "Redmond",
		"postalCode": "98052",
		"line1": "1 Microsoft Way"
	},
	"industry": "Software Development",
	"id": "1035",
	"followerCount": 20317859,
	"givenUrl": "https://www.linkedin.com/company/microsoft/"
}
```

## Output data documentation

Certainly, here is the JSON fields documentation without including the sample values:

**name** (string): The name of the company.

**description** (string): A detailed description of the company, including its mission, values, and culture.

**websiteUrl** (string): The URL to the company's website.

**employeeCount** (integer): The total number of employees at the company.

**specialities** (array of strings): An array of specialties or areas of expertise associated with the company.

**active** (boolean): Indicates whether the company is currently active.

**crunchbaseFundingData** (object): Contains information related to funding data from Crunchbase.

    - **numberOfFundingRounds** (integer): The total number of funding rounds.

    - **lastFundingRound** (object): Information about the most recent funding round.
    
        - **localizedFundingType** (string): The type of funding.

        - **leadInvestors** (array of strings): An array of lead investors.

        - **fundingRoundUrl** (string): The URL to the funding round details.

        - **announcedOn** (object): The date when the funding round was announced.

        - **numberOfOtherInvestors** (integer): The number of other investors.

        - **investorsUrl** (string): The URL to view all investors in the funding round.

    - **organizationUrl** (string): The URL to the company's Crunchbase organization profile.

    - **fundingRoundsUrl** (string): The URL to view all funding rounds associated with the company.

    - **updatedAt** (integer): A timestamp indicating the last update time for this Crunchbase data.


**adsRule** (string): A rule or status related to advertising.

**pageType** (string): The type of page.

 **logoUrl** (string): The URL to the company's logo image.

 **headquarter** (object): Information about the company's headquarters.

    - **country** (string): The country where the company's headquarters is located.

    - **geographicArea** (string): The geographic area within the country.

    - **city** (string): The city where the headquarters is situated.

    - **postalCode** (string): The postal code of the headquarters.

    - **line1** (string): The street address of the headquarters.


**industry** (string): The industry or sector to which the company belongs.

**id** (string): A unique identifier for the company.

**followerCount** (integer): The number of followers or subscribers to the company's profile.

**givenUrl** (string): The URL to the company's LinkedIn page.

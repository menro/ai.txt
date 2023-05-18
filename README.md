# ai.txt
An AI Standard for AI Web Crawling
{
  "datasetInfo": {
    "description": "This dataset contains Q&A pairs related to SEO, crawled from various websites and ranked based on user feedback.",
    "source": "Multiple websites",
    "crawlDate": "2023-05-16",
    "collectionMethod": "Web crawling with user feedback ranking",
    "dataAugmentation": "Back-translation and synonym replacement",
    "privacyPreserving": "Differential privacy",
    "dataBalance": "Balanced across various SEO topics",
    "legalConsiderations": "Data used with permission, no personal data collected",
    "contact": "data@company.com"
  },
  "website": {
    "url": "www.example.com",
    "crawlFrequency": "Weekly",
    "suggestedCrawlPages": ["/blog", "/faq"],
    "compressionTechniques": ["gzip"],
    "privacyConsiderations": ["No personal data collected"],
    "legalConsiderations": ["Data used with permission"],
    "compensation": "Free usage with attribution",
    "content": [
      {
        "question": "What is SEO?",
        "answer": "SEO stands for Search Engine Optimization, which is the practice of increasing the quantity and quality of traffic to your website through organic search engine results.",
        "keywords": ["SEO", "Search Engine Optimization", "traffic", "website", "organic search"],
        "rank": 5,
        "votes": {
          "upvotes": 100,
          "downvotes": 5
        },
        "metadata": {
          "dateAdded": "2023-05-16",
          "source": "User-generated",
          "language": "English",
          "otherLanguages": ["Spanish", "French"]
        },
        "augmentedData": [
          {
            "question": "Could you explain SEO?",
            "answer": "Certainly, SEO, or Search Engine Optimization, is a strategy used to increase the quality and quantity of website traffic via organic search engine results."
          },
          // More augmented Q&A pairs...
        ],
        "dataBalance": {
          "topic": "Digital Marketing",
          "percentage": 10
        }
      },
      // More Q&A pairs...
    ]
  },
  // More websites...
}

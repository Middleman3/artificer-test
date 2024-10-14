Generate a JSON object for an advertising strategy using the provided company context. Utilize the input parameters to create a detailed array of `ad_campaign` objects tailored for the company. Each `ad_campaign` object should encompass various elements necessary to outline a comprehensive advertising framework.

The input parameters include:
- `company_context`: Details about the company's identity, mission, and unique value propositions.
- `marketing_budget`: Total funding available for marketing activities.
- `brand_guidelines`: Rules that dictate visual style, tone, and messaging.
- `channel_catalog`: Available advertising channels and relevant information.
- `campaign_catalog`: Existing campaign strategies or historical data. 

# Company Context

## Focus for This Year
This year, the company's primary focus is expanding our digital product offerings to better serve a global audience. We aim to drive innovation through personalized solutions, increase engagement through our mobile platforms, and enhance the overall customer experience with a stronger emphasis on data-driven insights.

## Historic Demographic Foci
In the past, our key demographic focus has been professionals between the ages of 25-40, primarily located in North America and Europe. We have traditionally catered to tech-savvy individuals with disposable income and a need for advanced digital tools.

## Current Demographic Foci
Currently, we are targeting a more diverse global demographic. This includes emerging markets in Asia and South America, with a particular emphasis on younger users aged 18-35. We are also focusing on small and medium-sized businesses that can benefit from our scalable technology.

## Year-End KPIs/OKRs
1. Increase global user base by 25%.
2. Achieve a 40% mobile app adoption rate.
3. Boost customer retention by 15%.
4. Launch two new innovative product features.
5. Attain $10 million in annual recurring revenue.


# Brand Guidelines

## Logo Usage
- Use the company logo in its original form. Do not stretch, skew, or alter the logo.
- Maintain clear space around the logo to ensure visibility and impact. Minimum space should be equal to the height of the logo.

## Color Palette
- Primary Colors:
  - Hex: #003366 (Dark Blue)
  - Hex: #FFCC00 (Gold)
- Secondary Colors:
  - Hex: #FFFFFF (White)
  - Hex: #666666 (Gray)

## Typography
- Headings: Open Sans, Bold, 36pt
- Body Text: Roboto, Regular, 14pt

## Imagery Style
- Use high-quality, professional images that align with the company’s mission.
- Focus on diversity, inclusivity, and modern, innovative designs.

## Tone of Voice
- Professional but approachable.
- Confident yet empathetic.
- Customer-centric with a focus on delivering value.

## Social Media Guidelines
- Use a consistent tone of voice across all platforms.
- Always include the logo or brand identifier when posting.
- Engage with the audience in a friendly and respectful manner.



# Marketing Budget
```json
{
    "marketing_budget": 1000000,
    "currency": "USD"
}
```

# Channel Catalog
```json
{
    "Facebook": {
    "ad_types": [
        {
        "type": "Image Ad",
        "name": "Image Ad",
        "specifications": {
            "dimensions": "1200x628 px",
            "character_limit": 125,
            "file_size_limit": "30 MB",
            "formats": ["JPG", "PNG"]
        },
        "bidding_strategy": [
            "Cost per Click (CPC)",
            "Cost per Mille (CPM)",
            "Cost per Action (CPA)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        },
        {
        "type": "Video Ad",
        "name": "Video Ad",
        "specifications": {
            "dimensions": "1080x1080 px",
            "character_limit": 125,
            "video_length_limit": "15 seconds",
            "file_size_limit": "4 GB",
            "formats": ["MP4", "MOV"]
        },
        "bidding_strategy": [
            "Cost per Mille (CPM)",
            "Cost per View (CPV)",
            "Cost per Action (CPA)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        },
        {
        "type": "Carousel Ad",
        "name": "Carousel Ad",
        "specifications": {
            "image_dimensions": "1080x1080 px",
            "character_limit_per_card": 40,
            "max_cards": 10,
            "file_size_limit": "30 MB",
            "formats": ["JPG", "PNG"]
        },
        "bidding_strategy": [
            "Cost per Click (CPC)",
            "Cost per Mille (CPM)",
            "Cost per Action (CPA)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        }
    ]
    },
    "Instagram": {
    "ad_types": [
        {
        "type": "Image Ad",
        "name": "Photo Ad",
        "specifications": {
            "dimensions": "1080x1080 px",
            "character_limit": 2200,
            "file_size_limit": "30 MB",
            "formats": ["JPG", "PNG"]
        },
        "bidding_strategy": [
            "Cost per Click (CPC)",
            "Cost per Mille (CPM)",
            "Cost per Engagement (CPE)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        },
        {
        "type": "Video Ad",
        "name": "Story Ad",
        "specifications": {
            "dimensions": "1080x1920 px",
            "character_limit": 125,
            "video_length_limit": "15 seconds",
            "file_size_limit": "4 GB",
            "formats": ["MP4", "MOV"]
        },
        "bidding_strategy": [
            "Cost per Mille (CPM)",
            "Cost per View (CPV)",
            "Cost per Action (CPA)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        },
        {
        "type": "Video Ad",
        "name": "Reel Ad",
        "specifications": {
            "dimensions": "1080x1920 px",
            "character_limit": 125,
            "video_length_limit": "30 seconds",
            "file_size_limit": "4 GB",
            "formats": ["MP4", "MOV"]
        },
        "bidding_strategy": [
            "Cost per Mille (CPM)",
            "Cost per View (CPV)",
            "Cost per Action (CPA)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        }
    ]
    },
    "Google": {
    "ad_types": [
        {
        "type": "Text Ad",
        "name": "Search Ad",
        "specifications": {
            "headline_character_limit": 30,
            "description_character_limit": 90,
            "number_of_headlines": 3,
            "number_of_descriptions": 2
        },
        "bidding_strategy": [
            "Cost per Click (CPC)",
            "Cost per Conversion (CPC)",
            "Maximize Clicks"
        ],
        "payment_process": "Post-click invoicing or prepaid"
        },
        {
        "type": "Image Ad",
        "name": "Display Ad",
        "specifications": {
            "dimensions": [
            "300x250 px",
            "728x90 px",
            "160x600 px",
            "300x600 px",
            "970x250 px"
            ],
            "file_size_limit": "150 KB",
            "formats": ["JPG", "PNG", "GIF"]
        },
        "bidding_strategy": [
            "Cost per Mille (CPM)",
            "Cost per Click (CPC)",
            "Cost per Action (CPA)"
        ],
        "payment_process": "Post-click invoicing or prepaid"
        },
        {
        "type": "Video Ad",
        "name": "Video Ad",
        "specifications": {
            "dimensions": "1920x1080 px",
            "video_length_limit": "15 seconds",
            "file_size_limit": "4 GB",
            "formats": ["MP4", "MOV"]
        },
        "bidding_strategy": [
            "Cost per View (CPV)",
            "Cost per Action (CPA)",
            "Cost per Mille (CPM)"
        ],
        "payment_process": "Post-click invoicing or prepaid"
        }
    ]
    },
    "LinkedIn": {
    "ad_types": [
        {
        "type": "Image Ad",
        "name": "Sponsored Content",
        "specifications": {
            "dimensions": "1200x627 px",
            "character_limit": 150,
            "file_size_limit": "30 MB",
            "formats": ["JPG", "PNG"]
        },
        "bidding_strategy": [
            "Cost per Click (CPC)",
            "Cost per Mille (CPM)",
            "Cost per Lead (CPL)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        },
        {
        "type": "Text Ad",
        "name": "Message Ad",
        "specifications": {
            "character_limit": 500,
            "file_size_limit": "30 MB",
            "formats": ["Text"]
        },
        "bidding_strategy": [
            "Cost per Send",
            "Cost per Open (CPO)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        },
        {
        "type": "Image Ad",
        "name": "Dynamic Ad",
        "specifications": {
            "dimensions": "300x250 px",
            "file_size_limit": "150 KB",
            "formats": ["JPG", "PNG"]
        },
        "bidding_strategy": [
            "Cost per Click (CPC)",
            "Cost per Mille (CPM)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        }
    ]
    },
    "Twitter": {
    "ad_types": [
        {
        "type": "Text Ad",
        "name": "Promoted Tweet",
        "specifications": {
            "character_limit": 280,
            "file_size_limit": "5 MB for images, 15 MB for video",
            "formats": ["JPG", "PNG", "MP4", "MOV"]
        },
        "bidding_strategy": [
            "Cost per Engagement (CPE)",
            "Cost per Click (CPC)",
            "Cost per Mille (CPM)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        },
        {
        "type": "Video Ad",
        "name": "Promoted Video",
        "specifications": {
            "dimensions": "1920x1080 px",
            "video_length_limit": "2 minutes 20 seconds",
            "file_size_limit": "1 GB",
            "formats": ["MP4", "MOV"]
        },
        "bidding_strategy": [
            "Cost per View (CPV)",
            "Cost per Action (CPA)",
            "Cost per Mille (CPM)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        },
        {
        "type": "Carousel Ad",
        "name": "Carousel Ad",
        "specifications": {
            "image_dimensions": "1080x1080 px",
            "character_limit_per_card": 40,
            "max_cards": 6,
            "file_size_limit": "30 MB",
            "formats": ["JPG", "PNG"]
        },
        "bidding_strategy": [
            "Cost per Click (CPC)",
            "Cost per Mille (CPM)",
            "Cost per Action (CPA)"
        ],
        "payment_process": "Prepaid or monthly invoicing"
        }
    ]
    }
  }
  
```
# Campaign Catalog
```json
{
    "campaigns": {
      "awareness": {
        "description": "Designed to build brand awareness and reach a broad audience, focusing on maximizing impressions and reach.",
        "objectives": [
          "Brand awareness",
          "Reach"
        ],
        "strategies": [
          {
            "name": "Broad Reach",
            "description": "Maximizing the number of unique users who see the ad, targeting a large audience with minimal restrictions.",
            "targeting_criteria": [
              "Geographic targeting",
              "Demographic targeting"
            ],
            "bidding_strategy": "Cost per Mille (CPM)",
            "ad_types": [
              "Video Ad",
              "Display Ad",
              "Banner Ad",
              "Story Ad"
            ]
          },
          {
            "name": "Video Views",
            "description": "Focusing on delivering video content to users to drive brand recall and recognition.",
            "targeting_criteria": [
              "Video completion rate",
              "Demographic targeting",
              "Interest-based targeting"
            ],
            "bidding_strategy": "Cost per View (CPV)",
            "ad_types": [
              "Video Ad",
              "In-Stream Video Ad",
              "Outstream Video Ad"
            ]
          }
        ],
        "key_performance_indicators": [
          "Impressions",
          "Reach",
          "Video views",
          "Ad recall"
        ]
      },
      "traffic": {
        "description": "Aimed at driving users to a specific destination, such as a website or app, to increase the number of visitors.",
        "objectives": [
          "Website traffic",
          "App traffic"
        ],
        "strategies": [
          {
            "name": "Click-Through Traffic",
            "description": "Driving users to a specific landing page or app through targeted advertising.",
            "targeting_criteria": [
              "Behavioral targeting",
              "Interest-based targeting",
              "Lookalike audiences"
            ],
            "bidding_strategy": "Cost per Click (CPC)",
            "ad_types": [
              "Search Ad",
              "Display Ad",
              "Banner Ad",
              "Carousel Ad"
            ]
          },
          {
            "name": "App Installs",
            "description": "Focusing on encouraging users to download and install a mobile app.",
            "targeting_criteria": [
              "Mobile device targeting",
              "Operating system targeting",
              "App usage targeting"
            ],
            "bidding_strategy": "Cost per Install (CPI)",
            "ad_types": [
              "Display Ad",
              "Video Ad",
              "App Install Ad"
            ]
          }
        ],
        "key_performance_indicators": [
          "Click-through rate (CTR)",
          "Website visits",
          "App installs",
          "Bounce rate"
        ]
      },
      "engagement": {
        "description": "Aimed at encouraging users to interact with content, such as liking, sharing, commenting, or following.",
        "objectives": [
          "Post engagement",
          "Page likes",
          "Shares",
          "Comments"
        ],
        "strategies": [
          {
            "name": "Social Engagement",
            "description": "Encouraging interactions with posts or content on social media platforms.",
            "targeting_criteria": [
              "Demographic targeting",
              "Interest-based targeting",
              "Retargeting"
            ],
            "bidding_strategy": "Cost per Engagement (CPE)",
            "ad_types": [
              "Photo Ad",
              "Video Ad",
              "Carousel Ad"
            ]
          },
          {
            "name": "Event Responses",
            "description": "Driving RSVPs or responses to an event posted on social media.",
            "targeting_criteria": [
              "Interest-based targeting",
              "Geographic targeting",
              "Retargeting"
            ],
            "bidding_strategy": "Cost per Response (CPR)",
            "ad_types": [
              "Event Ad",
              "Story Ad",
              "Photo Ad"
            ]
          }
        ],
        "key_performance_indicators": [
          "Likes",
          "Shares",
          "Comments",
          "Event RSVPs"
        ]
      },
      "conversions": {
        "description": "Aimed at driving a specific action, such as purchases, sign-ups, or other valuable conversions.",
        "objectives": [
          "Purchases",
          "Leads",
          "Sign-ups",
          "App installs"
        ],
        "strategies": [
          {
            "name": "Lead Generation",
            "description": "Focusing on generating leads through contact forms, email sign-ups, or other means of capturing user information.",
            "targeting_criteria": [
              "Lookalike audiences",
              "Interest-based targeting",
              "Retargeting"
            ],
            "bidding_strategy": "Cost per Lead (CPL)",
            "ad_types": [
              "Lead Ad",
              "Banner Ad",
              "Search Ad",
              "Carousel Ad"
            ]
          },
          {
            "name": "E-commerce Sales",
            "description": "Driving users to make purchases on an e-commerce site or app.",
            "targeting_criteria": [
              "Behavioral targeting",
              "Dynamic retargeting",
              "Interest-based targeting"
            ],
            "bidding_strategy": "Cost per Acquisition (CPA)",
            "ad_types": [
              "Shopping Ad",
              "Display Ad",
              "Dynamic Product Ad"
            ]
          }
        ],
        "key_performance_indicators": [
          "Conversion rate",
          "Cost per acquisition (CPA)",
          "Return on Ad Spend (ROAS)",
          "Leads generated"
        ]
      },
      "retargeting": {
        "description": "Aimed at reaching users who have previously interacted with the brand or visited the website, encouraging them to return and convert.",
        "objectives": [
          "Conversions",
          "Abandoned cart recovery"
        ],
        "strategies": [
          {
            "name": "Site Retargeting",
            "description": "Displaying ads to users who have previously visited the website but didn’t convert.",
            "targeting_criteria": [
              "Pixel-based targeting",
              "Behavioral targeting"
            ],
            "bidding_strategy": "Cost per Click (CPC)",
            "ad_types": [
              "Display Ad",
              "Dynamic Product Ad",
              "Shopping Ad"
            ]
          },
          {
            "name": "Email Retargeting",
            "description": "Sending personalized email ads to users who have previously visited the website or interacted with the brand.",
            "targeting_criteria": [
              "Email list retargeting"
            ],
            "bidding_strategy": "Cost per Email Sent (CPES)",
            "ad_types": [
              "Email Ad"
            ]
          }
        ],
        "key_performance_indicators": [
          "Return visits",
          "Conversion rate",
          "Cart abandonment recovery rate"
        ]
      },
      "product_launch": {
        "description": "Focused on creating excitement and awareness for a new product or service, with the goal of driving both awareness and early conversions.",
        "objectives": [
          "Product awareness",
          "Early adopter conversions"
        ],
        "strategies": [
          {
            "name": "Teaser Campaign",
            "description": "Building curiosity and anticipation for a product launch with limited information.",
            "targeting_criteria": [
              "Interest-based targeting",
              "Geographic targeting"
            ],
            "bidding_strategy": "Cost per Mille (CPM)",
            "ad_types": [
              "Video Ad",
              "Display Ad",
              "Story Ad"
            ]
          },
          {
            "name": "Launch Day Promotion",
            "description": "Maximizing visibility on the product launch day to drive traffic and conversions.",
            "targeting_criteria": [
              "Lookalike audiences",
              "Behavioral targeting"
            ],
            "bidding_strategy": "Cost per Acquisition (CPA)",
            "ad_types": [
              "Banner Ad",
              "Search Ad",
              "Video Ad"
            ]
          }
        ],
        "key_performance_indicators": [
          "Impressions",
          "Early sales",
          "Pre-orders"
        ]
      }
    }
  }
  
```
# Output Format

The output should be a JSON object structured as follows:

```json
{
  "advertising_strategy": [
    {
      "ad_campaign": {
        "selected_channels": [
          {
            "channel_name": "PlaceholderChannel1",
            "bidding_strategy": {
              "ad_type1": "PlaceholderBiddingStrategy",
              "ad_type2": "PlaceholderBiddingStrategy"
            }
          },
          {
            "channel_name": "PlaceholderChannel2",
            "bidding_strategy": {
              "ad_type1": "PlaceholderBiddingStrategy",
              "ad_type2": "PlaceholderBiddingStrategy"
            }
          }
        ],
        "targeting_parameters": {
          "age_range": "18-35",
          "locations": ["Location1", "Location2"],
          "interests": ["Interest1", "Interest2"]
        },
        "goal": "Increase brand awareness",
        "budget_breakdown": {
          "total": "X amount",
          "per_channel": {
            "Channel1": "Y amount",
            "Channel2": "Z amount"
          }
        },
        "schedule": {
          "start_date": "YYYY-MM-DD",
          "end_date": "YYYY-MM-DD",
          "frequency": "daily"
        },
        "analytics_tracking_plan": {
          "utm_setup": "Configured",
          "kpis": ["KPI1", "KPI2"]
        }
      }
    }
    // Additional ad_campaign objects as needed
  ]
}
```

# Examples

## Example 1: Input Parameters

- company_context: {"name": "EcoWear", "mission": "Sustainable clothing for all", "unique_value": "100% recycled materials"}
- marketing_budget: 50000
- brand_guidelines: {"tone": "Friendly and Informative", "primary_color": "#00FF00"}
- channel_catalog: ["Instagram", "Facebook", "Google Ads"]
- campaign_catalog: [{"strategy": "Seasonal promotions", "past_performance": "high engagement"}]

## Example 1: JSON Output

```json
{
  "advertising_strategy": [
    {
      "ad_campaign": {
        "selected_channels": [
          {
            "channel_name": "Instagram",
            "bidding_strategy": {
              "image_ads": "CPC",
              "story_ads": "CPM"
            }
          }
        ],
        "targeting_parameters": {
          "age_range": "18-35",
          "locations": ["United States", "Canada"],
          "interests": ["Eco-friendly products", "Fashion"]
        },
        "goal": "Increase brand awareness",
        "budget_breakdown": {
          "total": 30000,
          "per_channel": {
            "Instagram": 20000
          }
        },
        "schedule": {
          "start_date": "2023-11-01",
          "end_date": "2023-12-31",
          "frequency": "weekly"
        },
        "analytics_tracking_plan": {
          "utm_setup": "Configured for Instagram",
          "kpis": ["Website traffic", "Social media engagement"]
        }
      }
    }
    // Additional ad_campaign objects as needed
  ]
}
```

# Notes

- Ensure each ad campaign is tailored based on the `company_context`, making optimal use of `marketing_budget`.
- Each `selected_channel` should reflect an informed choice aligning with `channel_catalog`.
- Consideration of `brand_guidelines` is essential in defining tone and style within `ad_campaign`.
- Campaign strategies should be built or enhanced based on `campaign_catalog` historical performance.
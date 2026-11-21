# Smart India Hackathon Workshop
# Date:21/11/2026
## Reference Number:26014758
## Name:HARSITH JAIN K

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution:

Project name: HARVEST DIRECT("Bridge for Farmers")

An AI-powered, voice-first direct-trade platform that connects farmers and FPOs to consumers and bulk buyers. It also handles quality grading, pooled logistics and payments, so no middleman is needed.

 ## 1. Detailed explanation of the proposed solution

DIRECTHARVEST has three user groups and six core modules.

Users:

Farmers / FPOs: list produce by voice or photo, get fair-price guidance, and receive payment directly.
Bulk buyers: retailers, hotels, restaurants, hostels, institutions and processors.
Consumers: housing societies, communities and households, via pooled orders.

Core modules:

  1.  Voice-first, multilingual onboarding. Farmers speak in their own language (Tamil, Hindi, Telugu, etc.) to list crops, quantity and expected harvest date. It also works through WhatsApp or IVR for feature-phone users, and the app works offline and syncs later.

  2.  AI Quality Grader. The farmer takes 2-3 photos and an on-device vision model assigns a grade (A/B/C) and flags visible defects. A graded product gets a fair, transparent price and earns buyer trust, without a middleman inspecting it.
    
  3.  Fair Price Engine. It compares live mandi prices (Agmarknet / e-NAM data), demand forecasts and quality grade. It suggests a price band and enforces a price floor, so a farmer never sells below the local mandi modal price.

  4.  Pre-Harvest Commitments (our key innovation). Buyers pre-book produce 1-3 weeks before harvest at an agreed price band, using the AI demand forecast. Farmers know their buyer and price before harvest, which cuts distress selling and wastage.

  5.  Pooled Logistics with Return-Load Matching (our second innovation). The system groups nearby farmers' pickups into one route and matches them with trucks or tempos returning empty from cities. This is cheaper than dedicated transport. It uses AI route optimization with shelf-life awareness, so perishables are routed first.
     
  6.  Escrow Payments and Price Passport. The buyer's UPI payment is held in escrow and released to the farmer's bank account on delivery confirmation. Every order shows a Price Passport, a QR-linked breakdown of where each rupee went (farmer share, transport, platform fee). This makes the farmer's share transparent.

## 2. How it addresses the problem:

1.  Problem: Farmers don't know buyers or prices, so they depend on middlemen.

Solution: Farmers list produce directly on the platform. The Fair Price Engine suggests a price band and enforces a price floor, so farmers never sell below the local mandi price.


2.  Problem: Many layers of traders and commission agents raise prices.

Solution: Farmers and buyers trade directly through a contract on the platform. The platform charges only a small fixed fee, much lower than typical intermediary commissions.


3.  Problem: Distress selling at harvest because of surplus and perishability.
   
Solution: Pre-Harvest Commitments let buyers book produce before harvest, guided by AI demand forecasting. Farmers know their buyer and price in advance.


4.  Problem: High and unpredictable transport costs for small farmers.
   
Solution: Pooled logistics groups nearby pickups into one route, and return-load matching uses trucks that would otherwise travel empty, which lowers the cost.


5.  Problem: Low trust in quality and payment.

Solution: AI quality grading, escrow payments, FPO verification, and farmer and buyer ratings build trust on both sides.


6.  Problem: Language and digital literacy barriers.
   
Solution: A voice-first, regional-language design with WhatsApp/IVR support and an offline-first app makes the platform usable for farmers with limited literacy or poor connectivity.


## 3. Innovation and uniqueness
  ~Pre-harvest demand matching: most marketplaces only sell what is already harvested. We match supply with demand before harvest.
  ~Return-load logistics matching: a low-cost approach to the "last-mile" cost problem, using vehicles that would otherwise travel empty.
  ~Price Passport: a transparency layer showing consumers and farmers exactly where the money goes.
  ~AI quality grading on a basic smartphone: removes the need for physical inspectors.
  ~Inclusive access: voice, WhatsApp and IVR for farmers with limited literacy or smartphone use.
  ~Interoperable by design: built to plug into open networks such as ONDC and government data (Agmarknet, e-NAM), so it complements existing systems.

## METHODOLOGY AND PROCESS FOR IMPLEMENTATION:

<img width="1093" height="1658" alt="image" src="https://github.com/user-attachments/assets/1ee499b6-53f4-4cdc-9647-fc6e1192e108" />

## Feasibility and Viability:

## 1.Analysis of feasibility:

  Technical: every component uses mature, widely available tools (OR-Tools, TFLite, Prophet, UPI, Bhashini). An MVP is realistic within hackathon and pilot timelines.
  
  Data: mandi prices and weather data are available from public government sources.
  
  Operational: FPOs already aggregate farmers, so they serve as natural village hubs and trusted onboarding partners.
  
  Economic: revenue comes from a small transaction fee (kept well below typical intermediary commissions), logistics margin, and optional paid analytics for bulk buyers and FPOs.
  
  Policy fit: aligns with the government's push for FPOs, digital agriculture and open commerce (e-NAM, ONDC, Agri Stack).


## 2. Potential challenges and risks
  i. Farmer adoption and digital literacy: Farmers may use the platform less if the app feels complex or unfamiliar.
  
  ii. Cold start: Buyers won't join without enough supply, and farmers won't join without enough buyers.
  
  iii. Quality disputes: Buyers and farmers may disagree on the produce grade after delivery.
  
  iv. Logistics reliability: Delays in pickup or delivery can cause spoilage of perishable produce.
  
  v.  Payment and trust concerns: Farmers may fear non-payment, and buyers may fear receiving poor-quality produce.
  
  vi. Forecast inaccuracy: Wrong demand or price predictions, especially for volatile crops, can lead to losses.
  
  vii. Poor connectivity: Weak networks in rural areas can disrupt listing, ordering and payment.
  
  viii. Competition and incumbents: Existing traders and platforms may resist the change or compete aggressively.


## 3. Strategies for overcoming these challenges

1.Adoption: voice-first UI, regional languages, WhatsApp/IVR options, and training through FPOs and local "Kisan Mitra" agents.

2.Cold start: begin hyperlocal (one district, a few crops) with anchor buyers such as hostels, restaurants, retail chains and housing societies; use FPOs as the supply base.

3.Quality disputes: photo-based grading is time-stamped at pickup; a clear dispute policy with a partial-refund rule.

4.Logistics: shelf-life-aware routing, partnerships with local transporters and cold-storage hubs, and live tracking.

5.Trust and payments: escrow payment, FPO verification, and farmer and buyer ratings.

6.Forecast accuracy: start with high-volume crops with good price history, show confidence ranges instead of single numbers, and keep retraining on new data.

7.Connectivity: offline-first app with local caching and sync when online, plus SMS fallback.

8.Incumbents: position as a complement; local traders can join as registered buyers or logistics partners.

## Impact and Benefits
Remove These Lines
1. Potential impact on the target audience
2. Benefits of the solution (social, economic, environmental, etc.)

## Research and References
Remove These Lines
1. Details / Links of the reference and research work

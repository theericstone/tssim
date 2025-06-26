# tssim -- A Taylor Swift Surprise Venue Predictor

Predict where Taylor Swift is most likely to make a surprise appearance based on venue characteristics and booking patterns.

## Features

- **Smart Algorithm**: Prioritizes venues with regular shows where Taylor can easily "drop in"
- **5 Major Cities**: Richmond, Washington DC, Boston, Los Angeles, and New York City
- **Venue Rankings**: Top 10 venues per city ranked by surprise appearance probability
- **Deep Analysis**: Detailed breakdown of venue strengths, concerns, and wildcard factors
- **Song Predictions**: Bonus predictions of what songs she might perform

## Algorithm Weights

- Regular Shows (30%) - Venues with frequent programming
- Drop-in Friendly (25%) - How easily artists can make surprise bookings
- Intimacy (15%) - Smaller, more personal venues
- Fan Access (10%) - Easy for fans to attend
- Acoustics (8%) - Sound quality
- Uniqueness (7%) - Memorable/iconic settings
- Taylor History (3%) - Past connections
- Prestige (2%) - Venue reputation

## Getting Started

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <your-repo-url>
cd taylor-swift-predictor

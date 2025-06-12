# Photo Location App

A React Native mobile app for taking photos with automatic GPS coordinate storage, displaying them on both a map and in a list view.

## Features

- ?? Take photos with automatic GPS coordinate capture
- ??? View photos on an interactive map
- ?? Browse photos in a list format
- ?? Secure user authentication with Supabase Auth
- ?? Cloud storage for photos and location data
- ?? Search photos within a specified radius

## Tech Stack

- **Frontend**: React Native with Expo
- **Backend**: Supabase
- **Database**: PostgreSQL with Row Level Security
- **Storage**: Supabase Storage for photo files
- **Maps**: React Native Maps
- **Authentication**: Supabase Auth

## Supabase Configuration

- **Project URL**: https://vsoekycaaiwgccuyukfq.supabase.co
- **Database**: Table photo_locations with RLS enabled
- **Storage**: Bucket photo-locations for photo files
- **Features**: Spatial queries, automatic timestamps, secure policies

## Setup Instructions

1. Clone the repository
2. Install dependencies: npm install
3. Copy .env.example to .env and fill in your values
4. Create a storage bucket named photo-locations in your Supabase dashboard
5. Run the app: npm start

## Development

The app includes:
- Camera screen with GPS tagging
- Photo upload to Supabase Storage
- Map view with photo markers
- List view of photos
- User authentication
- Secure data with Row Level Security

## License

MIT License

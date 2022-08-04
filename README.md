# iOS_Photos.sqlite_Queries
iOS Photos.sqlite queries that may help with decoding data stored in `Photos.sqlite`. These queries are based on testing, research and some community published research. These queries were written to work for the Photos.sqlite database stored at: 

iOS: /private/var/mobile/media/PhotoData/Photos.Sqlite

Mac OS: /Users//Pictures/PhotosLibrary.photoslibrary/database/Photos.sqlite

The query output includes the decoded data and the original database column values. The original value might be listed before or after the decoded value, here are a few examples:

Flash Fired-1                CPLAssets-6              Native-Back-Camera-1              Native-App-8               Live-Photo-2
4-Visible via For You        0-Past Highlights        4-Unknown

Some community members reached out and suggested a great change/update to my ELSE statements. The ELSE statements will now provide an indication if the value is new and its decoding is unknown. Here is an example of what that looks like:

Unknown-New-Value!: 440

My research started in 2020 and since that time, I have continued to research and update the queries. The initial write up was posted via [Heather Mahalik’s blog](https://smarterforensics.com/). The write up was later reviewed and published by DFRWS [here](https://dfir.pubpub.org/pub/v19rksyf/release/1).

A follow-up blog was posted on 2021/11/23 and can be found [here](https://theforensicscooter.com/2021/11/23/photos-sqlite-queries/)

Blog update posted 2022/02/21 and can be found [here](https://theforensicscooter.com/2022/02/21/photos-sqlite-update-3/)

2022/03/26 Some queries were deleted in preparation of updates

2022/04/03 Queries were updated and beautified

2022/8/3 Queries updated thanks to suggestions from Jacques Boucher

References:

See blog postings at https://theforensicscooter.com/ for updated list of references.

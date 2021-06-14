---
title: Assignment 1
subtitle: Computer performance, reliability, and scalability calculation
author: Jane Doe
---

## 1.2 

#### a. Data Sizes

| Data Item                                  | Size per Item | 
|--------------------------------------------|--------------:|
| 128 character message.                     | 128 Bytes     |
https://docs.oracle.com/cd/E19253-01/817-6223/chp-typeopexpr-2/index.html

| 1024x768 PNG image                         | 3.15 MB       |
https://toolstud.io/photo/filesize.php?imagewidth=1024&imageheight=768

| 1024x768 RAW image                         | 40 MB         | 
https://toolstud.io/photo/filesize.php?imagewidth=1024&imageheight=768

| HD (1080p) HEVC Video (15 minutes)         | 878 MB        |
https://www.videoproc.com/edit-4k-video/video-size-calculator.htm

| HD (1080p) Uncompressed Video (15 minutes) | 2.75 GB       |
https://www.videoproc.com/edit-4k-video/video-size-calculator.htm

| 4K UHD HEVC Video (15 minutes)             | 3.98 GB       |
175 MB per minute
https://www.macxdvd.com/mac-video-converter-pro/4k-video-file-size.htm

| 4k UHD Uncompressed Video (15 minutes)     | 31.64 GB      |
2 GB per Minute
https://www.reviewgeek.com/6416/is-it-better-to-watch-a-4k-movie-on-blu-ray-or-through-streaming/

| Human Genome (Uncompressed)                | 750 MB        |


#### b. Scaling

|                                           | Size     | # HD | 
|-------------------------------------------|---------:|-----:|
| Daily Twitter Tweets (Uncompressed)       | 177 GB   |  0.017 (1 Hard Drive)|
(128*500000000)/1024/1024/1024 * 3 copies

| Daily Twitter Tweets (Snappy Compressed)  | 102GB    |   0.01  (1 Hard Drive)|
59 Gb/1.7 * 3 copies

| Daily Instagram Photos                    | 675TB    |  68    |
75,000,000 * 3.15 MB for Photos * 3 copies 

| Daily YouTube Videos                      | 21 TB    |  3    |
500 Hrs * 878 Mb for 15 Mins * 3 copies

| Yearly Twitter Tweets (Uncompressed)      | 63 TB    |  7    |
59 GB * 365 * 3 copies

| Yearly Twitter Tweets (Snappy Compressed) | 36 TB    |  4    |
34 GB * 365 * 3 copies

| Yearly Instagram Photos                   | 240 PB   |  24,576    |
225 TB * 365 * 3 copies

| Yearly YouTube Videos                     | 7.2 PB   | 737    |
7 TB *365 * 3 copies

#### c. Reliability
|                                    | # HD     | # Failures |
|------------------------------------|-----:|-----------:|
| Twitter Tweets (Uncompressed)      | 7        | 0.06 (1 Hard Drive)     |
| Twitter Tweets (Snappy Compressed) | 4        | 0.034    (1 Hard Drive) |
| Instagram Photos                   | 24,576   | 209                     |
| YouTube Videos                     | 737      | 7                       |

0.85 % Hard Drive Failures used for calculation as per https://www.backblaze.com/b2/hard-drive-test-data.html

#### d. Latency

|                           | One Way Latency      |
|---------------------------|---------------------:|
| Los Angeles to Amsterdam  | 112 ms               |
https://www.consoleconnect.com/locations/amsterdam/

| Low Earth Orbit Satellite | 90 ms                |
https://www.omniaccess.com/leo/

| Geostationary Satellite   | 300 ms               |
https://www.omniaccess.com/leo/

| Earth to the Moon         | 1200 ms              |
https://en.wikipedia.org/wiki/Earth%E2%80%93Moon%E2%80%93Earth_communication#:~:text=Propagation%20time%20to%20the%20Moon,milliseconds%20of%20wave%20travel%20time.

| Earth to Mars             | 10 minutes           | 

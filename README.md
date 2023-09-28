# Website Monitoring in Go
## Description
This Go application was developed to monitor websites listed in a text file called `sites.txt`. It periodically checks whether websites are online or offline and records the information in a log file called `logs.txt`. The log contains details about the site status and scan time.

### How to use
1. Clone the repository or download the source code to your machine:

```
git clone https://github.com/DanielPinheir/website-monitor.git
```
2. Navigate to the project directory:

```
cd monitor-de-sites
```
3. Create a `sites.txt` file in the project root and enter the URLs of the sites you want to monitor, one per line:

```
https://www.site1.com
https://www.site2.com
https://www.site3.com
```
4. Run the application::

```
go run main.go
```
5. The application will start checking the sites listed in `sites.txt` and record the results in the `logs.txt` file.

> Logs will be recorded as follows in the file `logs.txt`:

```
[2023-09-27 20:15:00] Site https://www.site1.com is ONLINE
[2023-09-27 20:15:30] Site https://www.site2.com is OFFLINE
[2023-09-27 20:16:00] Site https://www.site3.com is ONLINE
```
***Language:***
`Golang`
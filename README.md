###### [(ระบบนี้ Transfer มาจาก Github Account เก่า --> https://github.com/TOEYJIRAKIT/HTML-BookingCampWebsite?tab=readme-ov-file)](https://github.com/TOEYJIRAKIT/HTML-BookingCampWebsite?tab=readme-ov-file)

## 🚀 **Project Name** :

JUSTCAMP – Tent Booking Web Application

## 📌 **Project Overview** :

JUSTCAMP is an innovative and user-friendly web application designed to make the process of booking camping sites seamless, quick, and hassle-free. In today’s fast-paced world, nature-based tourism and **camping** have become increasingly popular as people seek a break from urban life. **JUSTCAMP** serves as the perfect solution for camping enthusiasts, offering a streamlined platform to easily find, reserve, and manage their camping trips.

## 🙏 **Project Member** :

- 64102080 นายจิรกิตติ์ เอียดเหตุ
- 64125735 นายธนวัฒน์ กองสีสังข์
- 64104458 นางสาวณัฐธิดา ยะลา

## 🎯 **Objective** :

- Simplify the camping site booking process for users.
- Provide an intuitive and responsive user interface for a seamless experience.
- Store and manage booking data efficiently using JSON Server.

## ✨ **Key Features** :

- **Home** – Displays an overview of available camping sites and featured locations.
- **Booking** – Allows users to select a campsite, choose dates, and confirm their reservation.
- **Category** – Provides filtering options based on location, price, and amenities.
- **Contact** – Includes contact details and a form for inquiries or support.

## 🛠 **Tech Stack** :

- **Frontend:** CSS3, HTML5, JavaScript, Bootstrap
- **Deployment:** GitHub Pages
- **Other:** JSON Server

## 📂 **GitHub Repository (Source Code)** :

- [https://github.com/TOEYJIRAKID/Camping-Booking-Website](https://github.com/TOEYJIRAKID/Camping-Booking-Website)

## ⚙️ **Installation & Setup** :

1. **Clone the repository**  
   ```bash
   git clone https://github.com/TOEYJIRAKID/Camping-Booking-Website.git
   ```  
2. **Install dependencies**  
   ```bash
   npm install
   ```  
3. **Run the JSON Server**  
   ```bash
   npx json-server data.json --watch --port 3000
   ```  
4. **Open http://localhost:3000/history to view the json data.**

## 🏛️ **Database Structure** :

The application stores essential information related to each booking, ensuring smooth operations and accurate records:  
- **Location**: The camping site where the customer plans to stay.
- **Check-in**: The date the customer checks in, helping the system track bookings for that day.
- **Check-out**: The date the customer checks out, allowing the system to prepare for the next guest.
- **Number of guests**: Indicates how many people will be staying, assisting in calculating service fees accordingly.
- **Name**: Confirms the customer’s identity and ensures a valid booking.
- **Telephone**: An additional contact method to confirm and verify the booking.

|  #  | Attribute         | Description   | Data Type     | Example        | 
| ----| -------------     | ------------- | ------------- | -------------  | 
| 1   | Location          | The camping name | String        | Pha Hin Dam    |
| 2   | Check-in          | Date of arrival | String        | 2023-01-01     |
| 3   | Check-out         | Date of departure | String        | 2023-01-05     |
| 4   | Number of guests  | Total number of campers | Integer       | 6              |
| 5   | Name     | Full name of the customer | String        |jirakid aiadhet |
| 6   | Telephone         | Contact number | String        | 0950729219     |

## 📃 Example JSON Data :

Here’s a sample of how booking data is structured in JSON format:

```json
{
  "history": [
    {
      "camp": "Pha Hin Dam",
      "start_date": "2023-01-01",
      "end_date": "2023-01-05",
      "guest_total": "6",
      "guest_name": "jirakid aiadhet",
      "tel": "0999999999",
      "id": 1
    },
    {
      "camp": "9 Hua Camp Khaokho",
      "start_date": "2023-01-17",
      "end_date": "2023-01-27",
      "guest_total": "3",
      "guest_name": "somchai jaidee",
      "tel": "0999999999",
      "id": 2
    },
    {
      "camp": "Rai Hong Cha Kaj",
      "start_date": "2023-01-09",
      "end_date": "2023-01-07",
      "guest_total": "2",
      "guest_name": "somying jaiyak",
      "tel": "0999999999",
      "id": 3
    }
  ]
}
```

## 📽️ **Project Preview** :

![JUSTCAMP](https://github.com/TOEYJIRAKID/personal_gif_public/blob/main/Just-Camp-Preview.gif)

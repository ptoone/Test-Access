🧭 Test Access – HIV Testing Map (Ontario)

Test Access is a privacy-first, open map that helps people find organizations and clinics that offer HIV testing support across Ontario.

🔎 Search by postal code
📍 Filter by distance
🗺 Powered by OpenStreetMap + Leaflet
🔗 Shareable + embeddable

This tool is designed to make access to testing information easier — especially for people who may not know where to start.

🌍 Live Map

👉 https://testaccess.xyz.am/

🤝 Contributing Data

The most valuable way to contribute is by improving the locations dataset.

We welcome additions, corrections, and updates to:

Community organizations

Clinics

Mobile or outreach programs

Support centres that provide HIV testing or referrals

📁 Where the Data Lives

All locations are stored in:

main/data/ontario.json

Each entry looks like this:

{
  "id": "unique-id",
  "organization": "Organization Name",
  "address": "123 Example St",
  "city": "Toronto",
  "service_area": "Greater Toronto Area",
  "website": "https://example.org",
  "latitude": 43.6532,
  "longitude": -79.3832
}
🛠 How to Add or Edit a Location

Fork this repository

Edit main/data/ontario.json

Add or update an entry

Submit a Pull Request

✅ Data Guidelines

To keep the map useful and trustworthy:

✔ Include only real, verifiable services
✔ Confirm the organization offers testing or referrals
✔ Use official websites when possible
✔ Ensure latitude/longitude are accurate
✔ Avoid personal contact info unless publicly listed

If you're unsure, open an issue and we can review together.

❗ Important

This project does not guarantee service availability.

Always confirm hours, services, and eligibility with the organization directly.

🧩 Embedding the Map

You can embed the interactive map only (no header/hero) on any website.

Basic Embed
<iframe
  src="https://testaccess.xyz.am/?embed=1"
  width="100%"
  height="650"
  style="border:0;border-radius:12px;overflow:hidden"
  loading="lazy">
</iframe>
Embed with Custom View

The map supports a shareable view using coordinates:

#latitude,longitude,zoom

Example:

<iframe
  src="https://testaccess.xyz.am/?embed=1#43.6532,-79.3832,11"
  width="100%"
  height="650"
  style="border:0;border-radius:12px;overflow:hidden"
  loading="lazy">
</iframe>
🔐 Privacy

Searches stay in the user’s browser

No tracking scripts

Location data (if enabled) is never stored

⚠️ Disclaimer

This map is an informational tool intended to help people find HIV testing resources. It is not medical advice. In emergencies, contact local emergency services.

📬 Questions or Suggestions

Open an Issue or Pull Request — community contributions are what make this project better.

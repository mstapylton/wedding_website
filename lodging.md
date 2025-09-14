---
---
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Nearby Accommodations</title>
<style>
    :root{
        --ink:#17324a;
        --muted:#405b73;
        --rule:#d9cfc3;
    }
    body{
        margin:0;
        font-family: "Georgia", "Times New Roman", serif;
        color:var(--ink);
        background: none;
    }
    .wrap{
        max-width: 2100px; /* wider container */
    }
    h1{
        font-size: clamp(32px, 5vw, 64px);
        line-height: 1.05;
        text-align: center;
        margin: 0 0 6px;
        font-weight: 600;
        letter-spacing: .5px;
    }
    .sub{
        text-align:center;
        font-size: clamp(16px, 2.5vw, 28px);
        margin: 0 0 20px;
        color:var(--muted);
    }
    .card{
        background: none;
        border-radius: 0;
        overflow:hidden;
    }
    table{
        width:100%;
        border-collapse: collapse;
        font-size: clamp(14px, 1.5vw, 18px);
    }
    thead th{
        text-align:left;
        padding: 8px 14px; /* shorter row height */
        border-bottom: 2px solid var(--rule);
        font-weight: 700;
        letter-spacing:.3px;
    }
    tbody td{
        padding: 6px 14px; /* shorter row height */
        vertical-align: top;
        border-bottom: 1px solid #efe7db;
    }
    /* wider column distribution */
    thead th:nth-child(1) { width: 34%; }
    thead th:nth-child(2) { width: 18%; }
    thead th:nth-child(3) { width: 14%; }
    thead th:nth-child(4) { width: 14%; }
    thead th:nth-child(5) { width: 20%; }
    .stay{
        display:flex;
        gap:8px;
        align-items:flex-start;
        font-weight:600;
    }
    .icon{
        font-size: 18px;
        width: 24px;
        line-height: 1.2;
        text-align:center;
        opacity:.9;
        flex: 0 0 24px;
    }
    @media (max-width: 820px){
        thead{ display:none; }
        tbody td{
            display:block;
            border:none;
            padding:6px 14px;
        }
        tbody tr{
            border-bottom: 1px solid #efe7db;
        }
        tbody td[data-label]::before{
            content: attr(data-label) " ";
            display:block;
            font-variant: small-caps;
            letter-spacing: .08em;
            color: var(--muted);
            margin-bottom: 2px;
        }
        .stay{ margin-top: 6px; }
    }
</style>
</head>
<body>
    <main class="wrap">
        <h1>Nearby Accommodations</h1>
        <p class="sub">Estimated Jan 2026 Rates</p>
        <p class="sub">The nearby town of Jacó has more accomodation options too. We'll be arranging transport back to Jacó after the wedding.</p>
        <section class="card">
            <table aria-describedby="nearby accommodations">
                <thead>
                    <tr>
                        <th>Accommodation</th>
                        <th>Location</th>
                        <th>Luxury</th>
                        <th>Budget Tier</th>
                        <th>Highlights</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td data-label="Accommodation">
                            <div class="stay">
                                <span class="icon">🏨</span>
                                <span>Villa Caletas (standard rooms)</span>
                            </div>
                        </td>
                        <td data-label="Location">Villa Caletas<br/>Herradura</td>
                        <td data-label="Luxury">$500+</td>
                        <td data-label="Budget Tier">Luxury</td>
                        <td data-label="Highlights">Iconic views, infinity pool, spa, private beach access ~ same property as Zephyr Palace</td>
                    </tr>
                    <tr>
                        <td data-label="Accommodation">
                            <div class="stay">
                                <span class="icon">🏖️</span>
                                <span>Los Sueños Marriott Resort</span>
                            </div>
                        </td>
                        <td data-label="Location">Playa Herradura</td>
                        <td data-label="Luxury">$400</td>
                        <td data-label="Budget Tier">~ 10 min drive</td>
                        <td data-label="Highlights">Beachfront resort with spa, golf, marina, multiple dining options</td>
                    </tr>
                    <tr>
                        <td data-label="Accommodation">
                            <div class="stay">
                                <span class="icon">⛰️</span>
                                <span>Pumilio Mountain &amp; Ocean Hotel</span>
                            </div>
                        </td>
                        <td data-label="Location">Jacó</td>
                        <td data-label="Luxury">$400</td>
                        <td data-label="Budget Tier">~ 15 min drive</td>
                        <td data-label="Highlights">Boutique oasis with lazy river, spa, and tranquil gardens</td>
                    </tr>
                    <tr>
                        <td data-label="Accommodation">
                            <div class="stay">
                                <span class="icon">🏝️</span>
                                <span>Oceano Boutique Hotel &amp; Bistro</span>
                            </div>
                        </td>
                        <td data-label="Location">Jacó</td>
                        <td data-label="Luxury">$200–300</td>
                        <td data-label="Budget Tier">~ 20 min drive</td>
                        <td data-label="Highlights">Relaxed beachfront luxury with sunset views</td>
                    </tr>
                    <tr>
                        <td data-label="Accommodation">
                            <div class="stay">
                                <span class="icon">🌲</span>
                                <span>Hotel Punta Leona</span>
                            </div>
                        </td>
                        <td data-label="Location">Tárcoles</td>
                        <td data-label="Luxury">$200</td>
                        <td data-label="Budget Tier">~ 25 min drive</td>
                        <td data-label="Highlights">Scenic beach-and-mountain resort with family-friendly amenities</td>
                    </tr>
                </tbody>
            </table>
        </section>
    </main>
</body>
</html>

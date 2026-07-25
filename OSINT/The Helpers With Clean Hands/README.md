25th July 2026  <br>
Prepared by: Vplh  <br>
Difficulty: easy  <br>

The war of succession has ended on paper, but the Northern Crown Road still bleeds quietly. Villages that once resisted the Crown's claim now receive "mercy" from the Mercy Lantern Relief Trust — a charity delivering burial candles, lamp oil, and grief counselling to communities broken by the fighting. Behind the trust stands Ash & Wick Provisioners Ltd, a wholesale supplier of ceremonial goods whose invoices are clean, whose warehouse is spotless, and whose registered office is a letterbox on Cinder Lane. The charity's trustees believe they serve the grieving. The supplier's director, Nera Sorn, knows otherwise. Above Sorn sits Quiet Mercy Holdings Ltd, a non-trading shell wholly owned by a fiduciary foundation with restricted disclosure — a structure designed so that the same handful of names can sign both the purchase orders and the relief manifests without any single office ever being answerable. The next delivery is scheduled for Harrowgate. The receiving clerk is Sister Merrow. Somewhere in the tender records, the company filings, and the couriered dispatch notes, the chain of control runs from a charity that teaches mercy to a holding company that appoints the hands that make one possible. An intelligence desk has been set up with access to the Companies Register, the Tender Hall, an archive mirror, and the courier's intercepted mail. Trace the structure end to end and file the findings.
Use the Oath Submission form to confirm your findings, then assemble the flag from the verified answers.

Flag Format: HTB{SUPPLIER_FEEDS_TOWN}
Flag Example: HTB{COMPANY_NAME_FEEDS_DELIVERY_LOCATION}

<br>
Starting with the register for Mercy Lantern Relief Trust:

Appointed Persons:

Trustees:

	Sister Merrow
    Caldus Vey
    Orren Hald
	
Administrative Contact

    Ilyra Venn

Persons of interest:

Caldus Vey

    Director of Vey & Marr Corporate Services Ltd with Solen Marr
    Vey & Marr Corporate Services' business activities comprises of: Company secretarial services, registered office provision, compliance management
        Ownership is purely to the 2 directors.

Ilyra Venn

    Director of Quiet Mercy Holdings Ltd with Nera Sorn
    Quiet Mercy Holdings Ltd Non-trading holding company's business activities comprises of: management of subsidiary interests

<br>
<br>
Companies of interest: 

Ash & Wick Provisioners Ltd

    Ash & Wick Provisioners Ltd business activities comprises of: Wholesale ceremonial goods, municipal maintenance materials, funeral supplies
        Partial flag: This company supplies funeral supplies. 

Location: 

Email of interest:

Board approval — northern lots

    Sister Merrow has been notified as the receiving party
    The next uncompleted location mentioned in the email is "Harrowgate"

<br>
<br>
<details>
<summary>Final Flag</summary>

`HTB{ASH_AND_WICK_FEEDS_HARROWGATE}`

</details>

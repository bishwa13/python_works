the **entropy-based braiding index (eBI)** you screenshotted:

$$
H \;=\; -\sum_{i=1}^{N}\frac{w_i}{W}\,\log_2\!\left(\frac{w_i}{W}\right), \qquad eBI \;=\; 2^{H}
$$

Where each perpendicular cross-section has **N** active channels, **wᵢ** is the width of channel *i* (length of the line segment inside water), and **W = Σ wᵢ** is the total wet width.





----


Year,mean_H_bits,mean_eBI,mean_total_wet_width_m,mean_N_channels,Total_Water_Area_km2
1990,1.3675806726863238,3.1041960377866484,1319.4726477548231,5.2727272727272725,81.56709410615817
2000,1.0704192092631555,2.3886760921099173,1955.457574342781,4.136363636363637,132.99152088487176
2010,1.4584497444780895,3.0237198036893917,2122.5940082024663,5.681818181818182,123.67051386549117
2020,1.6499936233778518,3.4552621713646094,2127.90810785319,6.5,145.30818916386716
2024,1.687067918195991,3.478662233771282,1031.8829429610419,4.909090909090909,55.26083453056701


----


Hydraulic Entropy (H) and Effective Braid Index (eBI = 2ᴴ) using the formula in the image. Now, let’s interpret each column:

📊 Column meanings

Year – Observation year of river cross-section (1990, 2000, 2010, 2020, 2024).

mean_H_bits –

This is the average entropy H across all cross-sections for that year.

Higher H = more evenly distributed channel widths → river flow is more complex and braided.

Lower H = one or few channels dominate → river is simpler, less braided.

mean_eBI –

This is the effective braid index = 2ᴴ.

It tells the “effective” number of channels.

Example:

If H ≈ 1 → eBI ≈ 2 (like 2 effective channels).

If H ≈ 1.7 → eBI ≈ 3.5 (like ~3–4 effective channels).

mean_total_wet_width_m –

The average total width of all channels combined at cross-sections.

Wider values mean the river spread more water laterally (floodplain activity).

mean_N_channels –

The mean number of channels identified per cross-section.

This is the observed count of physical channels (not the “effective” one like eBI).

Total_Water_Area_km2 –

The total surface water area of the river system for that year (km²).

Indicates expansion or contraction of the river system’s wetted area.

🔎 Trend interpretation

1990 → 2000:

H dropped (1.36 → 1.07), eBI dropped (3.1 → 2.4).

Meaning: river became less braided (dominance of fewer channels).

But wet width and water area increased → perhaps a few wide channels dominated.

2000 → 2010:

H and eBI increased again → river became more braided.

Total wet width continued increasing.

2010 → 2020:

Significant rise in H (1.46 → 1.65) and eBI (3.0 → 3.45).

Mean N_channels also jumped (5.7 → 6.5).

Interpretation: river became highly braided with multiple channels.

2020 → 2024:

H and eBI stayed high, but wet width and water area dropped sharply.

Suggests: still braided but within a narrower corridor (maybe due to sedimentation, human intervention, or channel incision).

✅ So this table basically shows how the braiding intensity (H, eBI) and the physical size of the river (wet width, water area) evolved across decades.











Year  Average_Channel_Width_m  Water_Area_km2
0  1990               625.834453       81.567094
1  2000              1392.710468      132.991521
2  2010              1119.491179      123.670514
3  2020              1549.832157      145.308189
4  2024               733.208454       55.260835









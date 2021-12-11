- 👋 Hi, I’m @nguyen333
<!---
nguyen333/nguyen333 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->
_SECTION_BEGIN("Price Line");
PriceLineColor=ColorRGB(161, 202, 241);
Barsback = 500;
FirstBar = BarCount - BarsBack;
YY = IIf(BarIndex() >= Firstbar,EndValue(C),Null);
Plot(YY,"Current Price",PriceLineColor, 32|styleLine, 2);
_SECTION_END();

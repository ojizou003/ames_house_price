✕✅Lot Area：区画の広さ（平方フィート単位）
✅Garage Cars：ガレージの車容量
✅Overall Qual：住宅の全体的な材質と仕上げを評価する
✅Year Built：建築年        ラベルエンコード
✕✅Total Bsmt SF：地下室の総面積（平方フィート単位）
✅Fireplaces：暖炉の数
✅Full Bath：地上のフルバスルーム
✅Gr Liv Area
✕✅Garage Area
✕✅1st Flr SF

TotalSF = 1st Flr SF + 2nd Flr SF + Total Bsmt SF


✅Exter Qual：外装材の品質を評価する Gd=1 に変換
✅MS Zoning     dummy
✅Land Contour  Bnk=0 
✅Bldg Type     ラベルエンコード
✅Foundation    ラベルエンコード
✅Central Air   Ｎ=0, 
✅Neighborhood  ラベルエンコード
✕House Style   ラベルエンコード


'Order', 'MS SubClass', 'MS Zoning', 'Lot Area', 'Lot Shape',
       'Land Contour', 'Lot Config', 'Neighborhood', 'Bldg Type',
       'House Style', **'Overall Qual'**, 'Overall Cond', **'Year Built'**,
       'Year Remod/Add', 'Roof Style', 'Exterior 1st', 'Exterior 2nd',
       **'Exter Qual'**, 'Foundation', 'BsmtFin SF 1', 'Bsmt Unf SF',
       'Total Bsmt SF', 'Heating QC', 'Central Air', 'Electrical',
       '1st Flr SF', '2nd Flr SF', 'Gr Liv Area', 'Bsmt Full Bath',
       **'Full Bath'**, 'Half Bath', **'Bedroom AbvGr'**, 'Kitchen AbvGr',
       **'Kitchen Qual'**, 'TotRms AbvGrd', 'Fireplaces', 'Garage Cars',
       **'Garage Area'**, 'Paved Drive', 'Wood Deck SF', 'Open Porch SF',
       'Mo Sold', 'Yr Sold', 'Sale Type', 'Sale Condition', 'SalePrice'

use_columns = [~~'Lot Area',~~ 'Garage Cars', 'Overall Qual', 'Year Built', 'Total Bsmt SF', 'Fireplaces', 'Full Bath', 'Exter Qual', 'MS Zoning', 'Land Contour', 'Bldg Type', 'Foundation', 'Central Air', 'Neighborhood', ~~'Gr Liv Area'~~, '1st Flr SF', 'TotalSF']
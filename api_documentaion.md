# stats.nba.com Endpoints

## `leagueLeaders`

### Parameters 

* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`, `Per48`
* __Scope__:
  * Inferred Type: `str` 
  * Valid Values: `S`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `1974-75`, `2012-13`, `1972-73`, `2019-20`, `1967-68`, `1964-65`, `1987-88`, `1985-86`, `1953-54`, `1981-82`, `2009-10`, `1951-52`, `1954-55`, `1958-59`, `1946-47`, `2017-18`, `1999-00`, `2013-14`, `1994-95`, `1983-84`, `1956-57`, `1963-64`, `1984-85`, `2011-12`, `1978-79`, `2004-05`, `2015-16`, `2006-07`, `1966-67`, `1957-58`, `2014-15`, `2008-09`, `1998-99`, `1955-56`, `1996-97`, `1992-93`, `1997-98`, `2003-04`, `1969-70`, `1952-53`, `1977-78`, `1961-62`, `2005-06`, `1982-83`, `1993-94`, `1989-90`, `1988-89`, `1979-80`, `2018-19`, `1971-72`, `1965-66`, `1947-48`, `1970-71`, `2007-08`, `All Time`, `1976-77`, `1968-69`, `1962-63`, `2010-11`, `1973-74`, `1991-92`, `1959-60`, `1949-50`, `1960-61`, `1975-76`, `1948-49`, `1990-91`, `1980-81`, `1950-51`, `1995-96`, `2002-03`, `2016-17`, `2001-02`, `1986-87`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __StatCategory__:
  * Inferred Type: `str` 
  * Valid Values: `STL_TOV`, `OREB`, `MIN`, `STL`, `FGA`, `AST_TOV`, `FG3_PCT`, `FT_PCT`, `FG3A`, `TOV`, `REB`, `FTM`, `AST`, `PF`, `FTA`, `FG3M`, `BLK`, `DREB`, `PTS`, `FG_PCT`, `FGM`, `EFF`
* __ActiveFlag__:
  * Inferred Type: `bool` 
  * Valid Values: `Yes`, `No`

## `leaguedashplayerstats`

### Parameters 

* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __MeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Scoring`, `Usage`, `Misc`, `Base`, `Defense`, `Advanced`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `MinutesPer`, `Per48`, `PerPlay`, `PerPossession`, `PerMinute`, `Per40`, `Per100Plays`, `Per36`, `Totals`, `PerGame`, `Per100Possessions`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __TwoWay__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __DateFrom__:
  * Inferred Type: `date` 
  * Valid Values: `08/15/2020`
* __DateTo__:
  * Inferred Type: `date` 
  * Valid Values: `08/15/2020`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `leaguedashplayerclutch`

### Parameters 

* __AheadBehind__:
  * Inferred Type: `str` 
  * Valid Values: `Ahead or Behind`
* __ClutchTime__:
  * Inferred Type: `str` 
  * Valid Values: `Last 5 Minutes`
* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __MeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Scoring`, `Usage`, `Misc`, `Base`, `Advanced`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `MinutesPer`, `Per48`, `PerPlay`, `PerPossession`, `PerMinute`, `Per40`, `Per100Plays`, `Per36`, `Totals`, `PerGame`, `Per100Possessions`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PointDiff__:
  * Inferred Type: `int` 
  * Valid Values: `5`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `synergyplaytypes`

### Parameters 

* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`
* __PlayType__:
  * Inferred Type: `str` 
  * Valid Values: `OffScreen`, `OffRebound`, `Spotup`, `Isolation`, `PRRollman`, `Postup`, `Cut`, `Misc`, `Handoff`, `Transition`, `PRBallHandler`
* __PlayerOrTeam__:
  * Inferred Type: `bool` ,`str` 
  * Valid Values: `P`, `T`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __SeasonYear__:
  * Inferred Type: `str` 
  * Valid Values: `2017-18`, `2019-20`, `2015-16`, `2016-17`, `2018-19`
* __TypeGrouping__:
  * Inferred Type: `str` 
  * Valid Values: `defensive`, `offensive`

## `leaguedashptstats`

### Parameters 

* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`
* __PlayerOrTeam__:
  * Inferred Type: `str` 
  * Valid Values: `Player`, `Team`
* __PtMeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Drives`, `Possessions`, `Rebounding`, `ElbowTouch`, `PostTouch`, `PaintTouch`, `PullUpShot`, `Efficiency`, `Passing`, `Defense`, `CatchShoot`, `SpeedDistance`
* __Season__:
  * Inferred Type: `str` 
  * Valid Values: `2014-15`, `2017-18`, `2019-20`, `2013-14`, `2015-16`, `2016-17`, `2018-19`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `leaguedashptdefend`

### Parameters 

* __DefenseCategory__:
  * Inferred Type: `str` 
  * Valid Values: `Less Than 10Ft`, `Overall`, `Less Than 6Ft`, `Greater Than 15Ft`, `3 Pointers`, `2 Pointers`
* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __Season__:
  * Inferred Type: `str` 
  * Valid Values: `2014-15`, `2017-18`, `2019-20`, `2013-14`, `2015-16`, `2016-17`, `2018-19`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `leaguedashplayerptshot`

### Parameters 

* __GeneralRange__:
  * Inferred Type: `str` 
  * Valid Values: `Less Than 10 ft`, `Overall`, `Catch and Shoot`, `Pullups`
* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `str` 
  * Valid Values: `2014-15`, `2017-18`, `2019-20`, `2013-14`, `2015-16`, `2016-17`, `2018-19`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __ShotClockRange__:
  * Inferred Type: `str` 
  * Valid Values: `24-22`
* __DribbleRange__:
  * Inferred Type: `str` 
  * Valid Values: `0 Dribbles`
* __TouchTimeRange__:
  * Inferred Type: `str` 
  * Valid Values: `Touch < 2 Seconds`
* __CloseDefDistRange__:
  * Inferred Type: `str` 
  * Valid Values: `0-2 Feet - Very Tight`
* __ShotDistRange__:
  * Inferred Type: `str` 
  * Valid Values: `>=10.0`

## `leaguegamelog`

### Parameters 

* __Counter__:
  * Inferred Type: `int` 
  * Valid Values: `1000`
* __Direction__:
  * Inferred Type: `str` 
  * Valid Values: `DESC`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __PlayerOrTeam__:
  * Inferred Type: `bool` ,`str` 
  * Valid Values: `P`, `T`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `1974-75`, `2012-13`, `1972-73`, `2019-20`, `1967-68`, `1964-65`, `1987-88`, `1985-86`, `1953-54`, `1981-82`, `2009-10`, `1951-52`, `1954-55`, `1958-59`, `1946-47`, `2017-18`, `1999-00`, `2013-14`, `1994-95`, `1983-84`, `1956-57`, `1963-64`, `1984-85`, `2011-12`, `1978-79`, `2004-05`, `2015-16`, `2006-07`, `1966-67`, `1957-58`, `2014-15`, `2008-09`, `1998-99`, `1955-56`, `1996-97`, `1992-93`, `1997-98`, `2003-04`, `1969-70`, `1952-53`, `1977-78`, `1961-62`, `2005-06`, `1982-83`, `1993-94`, `1989-90`, `1988-89`, `1979-80`, `2018-19`, `1971-72`, `1965-66`, `1947-48`, `1970-71`, `2007-08`, `1968-69`, `1976-77`, `1962-63`, `1959-60`, `2010-11`, `1973-74`, `1991-92`, `1949-50`, `1960-61`, `1975-76`, `1948-49`, `1990-91`, `1980-81`, `1950-51`, `1995-96`, `2002-03`, `2016-17`, `2001-02`, `1986-87`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __Sorter__:
  * Inferred Type: `str` 
  * Valid Values: `DATE`

## `playergamelogs`

### Parameters 

* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __MeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Scoring`, `Usage`, `Misc`, `Base`, `Advanced`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`

## `leaguedashplayershotlocations`

### Parameters 

* __DistanceRange__:
  * Inferred Type: `str` 
  * Valid Values: `By Zone`, `5ft Range`, `8ft Range`
* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __MeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Opponent`, `Base`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`

## `leaguehustlestatsplayer`

### Parameters 

* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Per48`, `PerMinute`, `Per40`, `Per36`, `Totals`, `PerGame`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `str` 
  * Valid Values: `2017-18`, `2019-20`, `2015-16`, `2016-17`, `2018-19`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `alltimeleadersgrids`

### Parameters 

* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TopX__:
  * Inferred Type: `int` 
  * Valid Values: `10`

## `leaguedashplayerbiostats`

### Parameters 

* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `playoffpicture`

### Parameters 

* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __SeasonID__:
  * Inferred Type: `int` 
  * Valid Values: `22019`

## `leaguedashteamclutch`

### Parameters 

* __AheadBehind__:
  * Inferred Type: `str` 
  * Valid Values: `Ahead or Behind`
* __ClutchTime__:
  * Inferred Type: `str` 
  * Valid Values: `Last 5 Minutes`
* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __MeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Scoring`, `Four Factors`, `Opponent`, `Misc`, `Base`, `Advanced`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `MinutesPer`, `Per48`, `PerPlay`, `PerPossession`, `PerMinute`, `Per40`, `Per100Plays`, `Per36`, `Totals`, `PerGame`, `Per100Possessions`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PointDiff__:
  * Inferred Type: `int` 
  * Valid Values: `5`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `scoreboardV2`

### Parameters 

* __DayOffset__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __gameDate__:
  * Inferred Type: `date` 
  * Valid Values: `08/16/2020`, `08/04/2020`, `08/08/2020`, `08/05/2020`, `08/06/2020`, `08/15/2020`, `08/11/2020`, `08/12/2020`, `08/17/2020`, `08/02/2020`, `08/09/2020`, `08/18/2020`, `08/07/2020`, `08/03/2020`, `08/21/2020`, `08/14/2020`, `08/10/2020`, `08/19/2020`, `08/20/2020`, `08/13/2020`

## `leagueplayerondetails`

### Parameters 

* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __MeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Opponent`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `MinutesPer`, `Per48`, `PerPlay`, `PerPossession`, `PerMinute`, `Per40`, `Per100Plays`, `Per36`, `Totals`, `PerGame`, `Per100Possessions`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `playerestimatedmetrics`

### Parameters 

* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`

## `leaguedashteamstats`

### Parameters 

* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __MeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Scoring`, `Four Factors`, `Opponent`, `Misc`, `Base`, `Defense`, `Advanced`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `MinutesPer`, `Per48`, `PerPlay`, `PerPossession`, `PerMinute`, `Per40`, `Per100Plays`, `Per36`, `Totals`, `PerGame`, `Per100Possessions`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __TwoWay__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`
* __StarterBench__:
  * Inferred Type: `str` 
  * Valid Values: `Bench`

## `teamestimatedmetrics`

### Parameters 

* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`

## `leaguedashptteamdefend`

### Parameters 

* __DefenseCategory__:
  * Inferred Type: `str` 
  * Valid Values: `Less Than 10Ft`, `Overall`, `Less Than 6Ft`, `Greater Than 15Ft`, `3 Pointers`, `2 Pointers`
* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `PerGame`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __Season__:
  * Inferred Type: `str` 
  * Valid Values: `2014-15`, `2017-18`, `2019-20`, `2013-14`, `2015-16`, `2016-17`, `2018-19`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `leaguedashteamptshot`

### Parameters 

* __GeneralRange__:
  * Inferred Type: `str` 
  * Valid Values: `Less Than 10 ft`, `Overall`, `Catch and Shoot`, `Pullups`
* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `str` 
  * Valid Values: `2014-15`, `2017-18`, `2019-20`, `2013-14`, `2015-16`, `2016-17`, `2018-19`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __ShotClockRange__:
  * Inferred Type: `str` 
  * Valid Values: `24-22`
* __DribbleRange__:
  * Inferred Type: `str` 
  * Valid Values: `0 Dribbles`
* __TouchTimeRange__:
  * Inferred Type: `str` 
  * Valid Values: `Touch < 2 Seconds`
* __CloseDefDistRange__:
  * Inferred Type: `str` 
  * Valid Values: `0-2 Feet - Very Tight`
* __ShotDistRange__:
  * Inferred Type: `str` 
  * Valid Values: `>=10.0`

## `teamgamelogs`

### Parameters 

* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __MeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Scoring`, `Four Factors`, `Misc`, `Base`, `Advanced`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

## `leaguedashteamshotlocations`

### Parameters 

* __DistanceRange__:
  * Inferred Type: `str` 
  * Valid Values: `By Zone`, `5ft Range`, `8ft Range`
* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __MeasureType__:
  * Inferred Type: `str` 
  * Valid Values: `Opponent`, `Base`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Totals`, `PerGame`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `date` ,`str` 
  * Valid Values: `2000-01`, `2012-13`, `2019-20`, `2009-10`, `2017-18`, `1999-00`, `2013-14`, `2011-12`, `2004-05`, `2015-16`, `2006-07`, `2014-15`, `2008-09`, `1998-99`, `1996-97`, `1997-98`, `2003-04`, `2005-06`, `2018-19`, `2007-08`, `2010-11`, `2002-03`, `2016-17`, `2001-02`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`

## `leaguedashoppptshot`

### Parameters 

* __GeneralRange__:
  * Inferred Type: `str` 
  * Valid Values: `Overall`
* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `PerGame`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `str` 
  * Valid Values: `2019-20`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __ShotClockRange__:
  * Inferred Type: `str` 
  * Valid Values: `24-22`
* __DribbleRange__:
  * Inferred Type: `str` 
  * Valid Values: `0 Dribbles`
* __TouchTimeRange__:
  * Inferred Type: `str` 
  * Valid Values: `Touch < 2 Seconds`
* __CloseDefDistRange__:
  * Inferred Type: `str` 
  * Valid Values: `0-2 Feet - Very Tight`
* __ShotDistRange__:
  * Inferred Type: `str` 
  * Valid Values: `>=10.0`

## `leaguehustlestatsteam`

### Parameters 

* __LastNGames__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`, `13`, `14`
* __LeagueID__:
  * Inferred Type: `int` 
  * Valid Values: `00`
* __Month__:
  * Inferred Type: `str` 
  * Valid Values: `1`, `2`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `11`, `12`
* __OpponentTeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PORound__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PaceAdjust__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __PerMode__:
  * Inferred Type: `str` 
  * Valid Values: `Per48`, `PerMinute`, `Per40`, `Per36`, `Totals`, `PerGame`
* __Period__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __PlusMinus__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Rank__:
  * Inferred Type: `str` 
  * Valid Values: `N`
* __Season__:
  * Inferred Type: `str` 
  * Valid Values: `2017-18`, `2019-20`, `2015-16`, `2016-17`, `2018-19`
* __SeasonType__:
  * Inferred Type: `str` 
  * Valid Values: `All Star`, `Regular Season`, `Playoffs`
* __TeamID__:
  * Inferred Type: `int` 
  * Valid Values: `0`
* __SeasonSegment__:
  * Inferred Type: `str` 
  * Valid Values: `Post All-Star`, `Pre All-Star`

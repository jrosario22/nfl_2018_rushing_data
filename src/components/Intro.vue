<template>
  <div>
    <h1>Introducing The Data</h1>
    <p>
      I wanted to analyze this dataset to further understand the game of
      football. I am interested in the running aspect of the game.
    </p>
    <p>
      I found the dataset from Pro-Reference-Football. They utilize official NFL
      data. The dataset contains the 2018 rushing leaders for the season. Listed
      is the player's rank, name, team, age, position, games played, games
      started, rush attempts, rushing yards, rushing touchdowns, longest run,
      yards per attempt, yards per game, and fumbles.
    </p>
    <p>
      Note: At the time of download, first downs rushing was not part of my
      dataset. Players denoted with a * - selected for the Pro Bowl and + -
      First-Team All-Pro
    </p>
    <p>
      The dataset had some missing data. Players who did not play their position
      full-time had their position written in lowercase letters or missing. I
      filled in those positions with the position they were registered for in
      the beginning of the season.
    </p>
    <a href="https://www.pro-football-reference.com/years/2018/rushing.htm"
      >2018 NFL Rushing Leaders</a
    >
  </div>
</template>

<script>
export default {};
</script>

<style></style>

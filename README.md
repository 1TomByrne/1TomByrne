plan(multiprocess)
advanced_teams <- box_scores(game_ids = unique(games$idGame),
                             box_score_types = "Advanced",
                             result_types = "team")

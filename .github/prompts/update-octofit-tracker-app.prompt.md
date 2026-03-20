mode: 'agent'
model: GPT-4.1

# Django App Updates

- All Django project files are em `octofit-tracker/backend/octofit_tracker`.

1. Update `settings.py` para conexão MongoDB e CORS.
2. Atualize `models.py`, `serializers.py`, `urls.py`, `views.py`, `tests.py` e `admin.py` para suportar as coleções users, teams, activities, leaderboard e workouts.
3. Garanta que `/` aponta para a API e que `api_root` está presente em `urls.py`.

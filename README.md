1. **Слияние веток**: Когда вы сливаете одну ветку в другую, Git автоматически создает коммит слияния. Этот коммит содержит информацию о том, какие изменения были объединены.

2. **Коммиты в ветках Main и Develop**: Обычно в ветках Main и Develop не делают обычные коммиты, как в Feature. Эти ветки используются для слияния изменений из других веток. Коммиты в них появляются именно в результате слияния.

3. **Слияние из Main в Hotfix или из Develop в Release**: При слиянии изменений из одной ветки в другую также создается коммит слияния. Это стандартная практика в Git.
1.На локальном репозитории сделать ветки для:
- Postman  ===  git branch Postman
- Jmeter  ===  git branch Jmeter
- CheckLists  ===  git branch CheckLists
- BugReports  === git branch BugReports
- SQL  ===  git branch SQL
- Charles  ===  git branch Charles
- MobileTesting  ===  git branch MobileTesting

2. Запушить все ветки на внешний репозиторий  ===  git push -u origin "name our branch"
3. В ветке BugReports сделать текстовый документ со структурой баг репорта  ===  vim structure\_bug\_report.txt
4. Запушить структуру багрепорта на внешний репозиторий  ===  git add . && git commit -m"add txt file"  ===  git push
5. Вмержить ветку BugReports в Main  ===  находясь в ветке Main > git merge BugReports
6. Запушить main на внешний репозиторий  ===  git push
7. В ветке CheckLists набросать структуру чек листа  ===  vim structure\_checklist.txt
8. Запушить структуру чеклиста на внешний репозиторий  ===  git add . && git commit -m"add txt file"  ===  git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main  ===  Compare & pull request, main<CheckLists, comment, Create pull request, Merge pull request, Confirm
10. Синхронизировать Внешнюю и Локальную ветки Main  ===  git pull

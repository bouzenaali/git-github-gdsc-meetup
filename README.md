# Play the game
## Fork the Repository
<details>
<summary>Hint 1:</summary>
1. Click the "Fork" button in the top right corner to create your own copy.
</details>

## Clone the Repository
<details>
<summary>Hint 2:</summary>

Clone your forked repository to your local machine.

```bash
git clone https://github.com/bouzenaali/git-github-gdsc-meetup
```
</details>

## Edit the Code
<details>
<summary>Hint 3: </summary>

1. Open the `index.html` file in a text editor.
2. Look for a section that says Team display
3. Add your team, for example:

```html
      <!-- Team 1 -->
      <div class="team-box">
          <div class="member-box">Ali BOUZENA</div>
          <div class="member-box">Melissa GHEMARI</div>
      </div>
```
</details>

## Commit the Changes
<details>
<summary>Hint 4:</summary>

Add your changes to the staging area.

```bash
git add index.html
```
**or** 
```bash
git add .
```
Commit the changes with a meaningful message.

```bash
git commit -m "Add my team"
```
</details>

## Push to Your Repository
<details>
<summary>Hint 5:</summary>

Push your changes to your forked repository.

```bash
git push origin main
```
</details>

## Create a Pull Request
<details>
<summary>Hint 6:</summary>

1. Go to your forked repository on GitHub.
2. Click on the "New Pull Request" button.
3. Ensure the base repository is the original repository, and the base branch is `main`.
4. Ensure the head repository is your forked repository, and the compare branch is also `main`.
5. Click `Create Pull Request` and add a title and description.

</details>

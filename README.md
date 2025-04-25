# Quantum Enhanced Dot Product for Single Head Attention

## Git Workflow Guide

### Cloning the Repository

You can clone this repository using any of these methods:

#### Option 1: HTTPS URL

```bash
git clone https://github.com/DoQuantum/quantum-enhanced-dot-product-for-single-head-attention.git
```

#### Option 2: SSH URL

```bash
git clone git@github.com:DoQuantum/quantum-enhanced-dot-product-for-single-head-attention.git
```

#### Option 3: GitHub CLI

```bash
gh repo clone DoQuantum/quantum-enhanced-dot-product-for-single-head-attention
```

#### Option 4: Command Palette

1. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac)
2. Type "git clone"
3. Paste one of the URLs above
4. Choose your destination folder

### Branching Workflow

1. **Create a new branch**:

   ```bash
   git branch -c your-name/feature-name
   ```

2. **Stage and commit changes**:

   ```bash
   git add .
   # OR
   git add specific-file-name

   git commit -m "Your descriptive commit message"
   ```

3. **Push your branch**:

   ```bash
   git push origin feature-your-name
   # OR
   git push origin head
   ```

4. **Open a Pull Request** on GitHub:
   - Click "Compare & pull request"
   - Add description
   - Request review

### Keeping Your Repo Updated

```bash
git checkout main
git pull origin main
# Then create your feature branch from the updated main
```

### Best Practices

- One branch per feature or fix
- Pull frequently to avoid merge conflicts
- Keep code well-commented and organized
- Use clear commit messages
- Track bugs and tasks with GitHub Issues

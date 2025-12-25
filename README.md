# CV Rendering Project

Personal setup for generating my resume in English and French using [RenderCV](https://github.com/rendercv/rendercv).

## How to use

I've created a helper script to handle the rendering and cleanup.

- **English version**:
  ```bash
  ./render en
  ```
- **French version**:
  ```bash
  ./render fr
  ```

The PDF will be generated in the `rendercv_output/` directory.

## File Structure

- `EN-Resume.yaml`: Source for the English CV.
- `FR-Resume.yaml`: Source for the French CV.
- `images/`: Contains `profile_pic.png`.
- `render`: Bash script that runs `rendercv render` with specific flags (only generates PDF).

## Next Steps (Maybe)

- [ ] **GitHub Actions**: Automate rendering so the PDF updates whenever I push a Change to the YAML files.
- [ ] **Live Editing**: Add a script version with the `--watch` flag to see changes in real-time.
- [ ] **Custom Theme**: Explore customizing the `classic` theme beyond just colors if I get bored with the current look.
- [ ] **Versioning**: Tag releases when I apply for specific jobs to keep track of what I sent.

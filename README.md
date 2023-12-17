# Flying Robots Pequi Mecânico - 2024

Welcome to the Flying Robots Pequi Mecânico GitHub Organization Guide for our autonomous aerial robot development for the LARC 2023-2024 in Goiânia. Our goal is to engineer a robot capable of tasks such as localization, mapping unknown areas, object recognition, and artifact transportation.

## About the Team
The Flying Robots Pequi Mecânico team is dedicated to developing an autonomous aerial robot for competing in the Latin American Robotics Competition (LARC) 2024 in Goiânia. We aim to create a robot capable of performing tasks like localization, mapping unknown areas, object recognition, and artifact transport.

## Main Areas
- **Mechanics**: Physical design and construction of the robot.
- **Hardware**: Electronic components and systems integration.
- **Software**: Software development is divided into:
  - Perception
  - Autonomous (navigation, localization, mapping)
  - Human-Robot Interaction

## Repository Structure
Each main area will have its own repository with the following structure:
- `README.md`: Project description, installation, and usage.
- `docs`: Technical documentation and reports.
- `src`: Source code.
- `tests`: Automated tests.
- `examples`: Usage examples and demonstrations.
  
Plus, the repository must contain a description and tags related to the team and the working area. 

## Best Practices
1. **Commits and Messages**:
   - Use clear and descriptive messages.
   - Example: `git commit -m "Perception: Add sensor integration in perception module"`

2. **Issues and Tracking**:
   - Use issues to manage tasks and bugs.
   - Assign issues to responsible team members.

3. **Pull Requests and Code Review**:
   - Create pull requests for code reviews.
   - Request reviews from other team members.

4. **Branching**:
   - Use specific branches for new features or fixes.
   - Example: `git checkout -b feature/object-recognition`

5. **Documentation**:
   - Keep documentation up-to-date and clear.

6. **Security and Privacy**:
   - Do not share sensitive information.
   - Use the Issues Github's Tool to show and share possible problems you had while working with your code.

## Submodule Guide for Flying Robots Pequi Mecânico

Submodules are a Git tool that allows you to incorporate and track stable commit versions from an external repository within your main project's directory.

### Adding Submodules

To add a new submodule, execute the `git submodule add` command followed by the repository URL and the path where you want the submodule placed.

```bash
git submodule add <repository-url> <path-to-submodule>

```

## Contact and Communication
- For inquiries or collaborations, please reach out to us at pequi.flyingrobots@gmail.com.


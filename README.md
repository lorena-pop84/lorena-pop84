# Lorena Pop

Medical Engineering graduate (Politehnica University Timișoara). This is where I keep my finite element analysis projects, all done in Abaqus/CAE 6.14.

## Projects

| Project | Model setup | Main result |
|---|---|---|
| [Hand rehabilitation device](https://github.com/lorena-pop84/abaqus-hand-rehabilitation-device) (bachelor's thesis) | PETG lever with pivot and supports, static snapshot with forces in balance, about 39,000 hexahedral elements, 13 friction contact pairs | Max von Mises stress 3.3 MPa near the axle, max displacement 3.6 mm at the handle |
| [PIP finger-joint prosthesis](https://github.com/lorena-pop84/abaqus-finger-joint-prosthesis) | Four-part Ti-6Al-4V hinge, 10 N load with the hinge held at one fixed angle, about 56,000 hexahedral elements, friction contacts | Max von Mises stress 0.66 MPa, max contact pressure 0.90 MPa |
| [Medical IV stand](https://github.com/lorena-pop84/abaqus-medical-iv-stand) | Aluminium stand, tetrahedral mesh, ties and distributing couplings, two load cases (4 hooks × 5 N vs 1 hook × 15 N) | One loaded hook: about 2.5× higher stress and 42× more deflection |

## What I practiced

- Structured hexahedral meshing with manual partitioning
- Contact with friction, ties and couplings between parts
- Static analysis, with the load case chosen to match the real situation as closely as I could
- Reading results: stress, displacement, contact pressure

## Limits of these models

They are simplified, static studies. None of them has a mesh convergence study or physical measurements to compare against, so I treat the numbers as indicative. Each repo's README lists its own limitations.

## Opening the models

Each repo has a `models/` folder with the final `.inp` files. In Abaqus/CAE: File → Import → Model, then pick the `.inp` file. I used version 6.14.

## Portfolio

[lorena-pop84.github.io](https://lorena-pop84.github.io)

## Contact

[LinkedIn](https://www.linkedin.com/in/pop-lorena) · lorena.pop84@gmail.com

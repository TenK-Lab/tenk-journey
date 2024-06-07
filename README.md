# TenK Journey

Welcome to our Tenk Journey! 🚀 This place is like our startup's diary, where we share all the ups and downs of creating TenK Hours. From the cool stuff we're doing to the tricky bits we're figuring out, it's all here. Come hang out with us, learn with us, and let's make productivity a whole lot more fun together!

## Updates

- **07/06/2024:** Hieu bought the domain `tenkhours.org` from Namecheap (`tenkhours.com` was already registered by someone else). As we created an organization to manage the repos, we could not use Vercel to host it for free as we usually did before, lol. We would find an alternative way to host a dummy landing page, but let it be in another day.
- **05/06/2024:** [First survey (Vietnamese version)](<https://forms.gle/vywc6PyA1geoAtNx8>) created.
- **04/06/2024:** The minimal version of design system was ready on Figma.
- **03/06/2024:** Hieu recently chatted with his friend, Anh Tu, about their productivity app idea. Tu expressed skepticism, believing the TenK Hours approach would be sufficient for most people. Similarly, Hieu's conversations with others revealed a lack of initial enthusiasm. Based on this feedback, the team concluded a thorough survey is necessary to gauge market interest. Additionally, we believe developing a Minimum Viable Product and launching it quickly will provide valuable insights into user reception.
- **02/06/2024:**
  - Nhat Hung joined as a Graduation Project member, he became our first UX/UI designer. The Graduation Project team was filled with 6/6 members.
  - Successfully rendered a `.glb` file using  React Three Fiber with Expo SDK 50 on Android Emulator, Android Device. Thanks to [this tutorial](https://youtube.com/watch?v=SP0O5o9BJVA).
- **01/06/2024:** Our first development sprint officially began. Our next target is the "minimal" version.
- **29/05/2024:** Set up a minimal golang backend monorepo.
- **26/05/2024:**
  - We built our project workspace on Notion.
  - Our initial team meeting was held with four members (Hieu, Thu, Nam, and Nhan). We talked about our product idea, choosing the tech stack, picking scrum start date, finding new members, etc.
  - Following the meeting, Thanh Binh joined as a Graduation Project member, specializing in backend engineering.

- **23/05/2024 - 25/05/2024:** Hieu and Nhan Phu wanted to find out the appropriate way to render 3D models on mobile and further cross-platform. They decided to look for both Bare React Native, or Expo Framework, React Three Fiber or Babylon Native. There were some research results (disclaimer: the research was done by students with beginner-level):
  - Babylon Native: Hieu could not go further as he used an M1 Mac and faced [this issue](https://github.com/BabylonJS/BabylonReactNative/issues/451). The cost to develop with Babylon Native on arm64 binaries is to downgrade React Native to version 0.69. The team decided to wait for the R3F research result before taking any further steps.
  - Expo SDK 51 with R3F: we found the same issue as [this one](https://github.com/expo/expo/issues/29001).
  - Successfully rendered an example geometry using Expo SDK 49 and R3F on Android Emulator and Android Device. iOS Emulator not rendered (<https://github.com/pmndrs/react-three-fiber/issues/2546>) and iOS device cannot be tested as we did not find a way to rollback the Expo SDK version from 51 to 49 on its iOS app. This was a good sign, we would explore more based on this direction.
- **22/05/2024:** The Vinh joined as a Startup member with a product owner role.
- **21/05/2024:**
  - Hai Nam joined as a Graduation Project member with a full-stack role.
  - Internal discord server was created.
- **18/05/2024:** Nhan Phu joined as a Graduation Project member. His main role was a cloud engineer and a backend developer but he also helped create 3D models.
- **16/05/2024:** The initial concept for TenK Hours was defined, outlining three phases: TenK Core, TenK Enhancement, and TenK Connect.
- **Before 14/05/2024:** Hieu decided to use this idea for his graduation project. Graduation projects typically have a maximum of six members, so we're considering two scopes for this project: Startup and Graduation Project. Currently, TenK Hours has two initial members: Hieu and his girlfriend, Minh Thu. They are both involved in both the Startup and Graduation Project scopes.
- **Origin Story:** TenK Hours began as Hieu Nguyen's idea for a productivity app that helps users create visual diaries, not through words, but through a character-based system. Each character is a dynamic representation of a person, reflecting the various facets of their life. Characters embody unique aspects of interests, passions, and daily activities. Whether you're a dedicated "Software Engineer" by day, a "Gym God" in the evening, or a culinary enthusiast like "Gordon Ramsay at Home" by night, your characters grow and evolve based on the time and focus you invest in them. Customize your characters to mirror your journey, celebrate your achievements, and showcase the diverse sides of who you are.

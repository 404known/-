## <u>What is OpenCV?</u>

OpenCV stands for Open-Source Computer Vision (Library). It is the most common and popularly used, well-documented Computer Vision library. OpenCV is an open-source library that incorporates numerous computer vision algorithms. OpenCV increases computational efficiency and assists with real-time applications. One of the major goals of OpenCV is to provide an accessible and easy-to-use computer vision infrastructure that helps people build sophisticated computer vision applications quickly.

## <u>Features of OpenCV</u>

Main features of OpenCV-Python include:

1. **Cross-platform**: Allows installation for different environments (operating systems)

2. **Portable**: Transferable to any machine that can run C.

3. **Open source**: OpenCV is free for use under the open-source Apache 2 License.

4. **Fast**: OpenCV is highly optimized and makes use of NumPy functions.

5. **Vast algorithms**: OpenCV packages contain more than 2500 algorithms.

6. **Fast prototyping:** Implemented in the development of real-time applications.

7. **Extensive use**: Used across various organizations and companies.

## <u>Context</u>

OpenCV was initiated at Intel in the year 1999 by Gary Bradsky. The first release of OpenCV came later in the year 2000. It was originally developed by Intel employees in a research center in Russia, but the project was taken over by a non-profit organization in 2012. OpenCV supports a multitude of Computer Vision and Machine Learning algorithms that are ever-growing.

In the initial stages of OpenCV, the goals of the company were as follows:

1. They sought to make advanced computer vision more accessible by providing open and optimized code for computer vision implementation.
2. The company aimed to essential open-source computer vision knowledge by providing a common platform that developers could build on, to make the code readily readable and transferable.
3. Deliver advanced commercial applications of computer vision by making portable and optimized code available for development. The OpenCV’s license provided the developers with the freedom to choose whether to open-source their product or not.



## <u>Quality attribute</u>

1. Usablity. OpenCV supports a wide range of programming languages which include C++, Java, Python, etc. This is a cross-platform library that supports Windows, Linux, macOS, Android, and iOS.

2. Performance. It plays a major role in real-time image processing and computer vision tasks which is a necessity for modern applications. OpenCV makes use of NumPy, which is a highly optimized python library for numerical computations. All of the OpenCV array structures are converted to and from NumPy arrays.

3. Scalability. OpenCV now supports many algorithms related to computer vision and machine learning, and it is expanding every day.

## <u>Key Driver</u>

1. Cross-platform

The key design idea is to keep pipeline code itself platform-neutral while specifying which kernels to use and which devices to utilize using extra parameters at graph compile (configuration) time.

2. Scalability

The system based on machine vision has realized the advantages of intelligence, full automation and high precision of products. However, with the wider use of machine vision, the machine vision detection technology also needs to be constantly developed, so that when accessing different systems, it can improve efficiency and ensure reliability.

## <u>Early Decision</u>

早期决策要关注怎么做（solution），分析这么做的好处，可能关系较少

1. Advance vision research by providing not only open but also optimized code for basic vision infrastructure. No more reinventing the wheel. 
2. OpenCV should provide user a API-layer which he can intercacts with directly and hide the entities the user operates on. It will make openCV easier to use and platform-neutral.
3. OpenCV should provide an intermediate layer which unrolls user computation into a graph and then applies a number of transformations to it. 
4. OpenCV should provide many backends layers which are highly coupled with low-level platform details, with every backend standing for every platform.
5. OpenCV handles all the memory automatically.

## <u>StakeHolder And the Specific Concerns</u>

### User

The people who use openCV to develop machine vision application or study machine vision.

#### Main Concerns

1. Whether necessary functionality about machine vision is being delivered. 
2. Whether openCV is easy to use.
3. Whether openCV is high-performanced.

### Project Manager

Responsible for planning, sequencing, scheduling, and allocating resources to develop software components and deliver components to integration and test activities.

#### Main Concerns

1. Whether openCV can be delivered on time.
2. Whether openCV has efficient image processing capability.

### Tester

Creating tests based on the behavior and interaction of the software elements. 

#### Main Concerns

1. Whether openCV is correctly developed.

## <u>Technical Context</u>

1. Performance. OpenCV makes use of NumPy functions, which makes matrix calculation faster. But computational performance declines when facing large amounts of data.
2. Scalability. OpenCV uses G-API framework and provides an unified API to program image processing pipelines with a number of supported backends.


<h1>Hw3</h1>

```swift



import SwiftUI
struct ContentView: View {
    var body:some View{
        ZStack {
            Image("Bg1")
                .resizable()
            //.aspectRatio(contentMode:.fit)
                .frame(width:600, height: 770, alignment: .center)
            VStack {
                HStack {
                    P1View()
                    P2View()
                    P3View()
                }
                HStack {
                    P4View()
                    P5View()
                    P6View()
                }
                HStack {
                    P7View()
                    P8View()
                    P9View()
                }
            }
        }
    } 
}
struct P1View: View {
    var body: some View {
        VStack {
            Image("P1")
                .resizable()
                .aspectRatio(contentMode:.fit)
            //.frame(width: UIScreen.screenWidth/2-20,alignment: .center)
            Text("dog")
                .fontWeight(.bold)
                .font(.system(size: 30))
        }
    }
}

struct P2View: View{
    var body: some View{
        VStack {
            Image("P2")
                .resizable()
                .aspectRatio(contentMode:.fit)
            //.frame(width: UIScreen.screenWidth/2-20,alignment: .center)
            Text("anya")
                .fontWeight(.bold)
                .font(.system(size: 30))
        }//.padding(.all, 2)
    }
}

struct P3View: View{
    var body: some View{
        VStack {
            Image("P3")
                .resizable()
                .aspectRatio(contentMode:.fit)
            //.frame(width: UIScreen.screenWidth/2-20,alignment: .center)
            Text("kirby")
                .fontWeight(.bold)
                .font(.system(size: 30))
        }
    }
}

struct P4View: View{
    var body: some View{
        VStack {
            Image("P4")
                .resizable()
                .aspectRatio(contentMode:.fit)
            //.frame(width: UIScreen.screenWidth/2-20,alignment: .center)
            Text("bunny")
                .fontWeight(.bold)
                .font(.system(size: 30))
        }
    }
}

struct P5View: View{
    var body: some View{
        VStack {
            Image("P5")
                .resizable()
                .aspectRatio(contentMode:.fit)
            //.frame(width: UIScreen.screenWidth/2-20,alignment: .center)
            Text("gojo")
                .fontWeight(.bold)
                .font(.system(size: 30))
        }
    }
}

struct P6View: View{
    var body: some View{
        VStack {
            Image("P6")
                .resizable()
                .aspectRatio(contentMode:.fit)
            //.frame(width: UIScreen.screenWidth/2-20,alignment: .center)
            Text("vampire")
                .fontWeight(.bold)
                .font(.system(size: 30))
        }
    }
}

struct P7View: View{
    var body: some View{
        VStack {
            Image("P7")
                .resizable()
                .aspectRatio(contentMode:.fit)
            //.frame(width: UIScreen.screenWidth/2-20,alignment: .center)
            Text("ja")
                .fontWeight(.bold)
                .font(.system(size: 30))
        }
    }
}

struct P8View: View{
    var body: some View{
        VStack {
            Image("P8")
                .resizable()
                .aspectRatio(contentMode:.fit)
            //.frame(width: UIScreen.screenWidth/2-20,alignment: .center)
            Text("kobe")
                .fontWeight(.bold)
                .font(.system(size: 30))
        }
    }
}

struct P9View: View{
    var body: some View{
        VStack {
            Image("P9")
                .resizable()
                .aspectRatio(contentMode:.fit)
            //.frame(width: UIScreen.screenWidth/2-20,alignment: .center)
            Text("devil")
                .fontWeight(.bold)
                .font(.system(size: 30))
        }
    }
}

```

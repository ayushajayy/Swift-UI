Here it is..

//  ContentView.swift
//  uitest
//  Created by Ayush on 04/07/21.
import SwiftUI
struct ContentView: View {
    var body: some View {
        
        VStack(spacing:50) {
            ZStack(){
            Image("toronto")
                .resizable()
                .aspectRatio(contentMode: /*@START_MENU_TOKEN@*/.fit/*@END_MENU_TOKEN@*/)
                .frame(width: 330.0, height: 330.0)
                .cornerRadius(15.0)
                
                VStack(spacing:0){
                    Text("CN Tower").font(.title).foregroundColor(Color.white).padding()
                        .background(Color.black).opacity(0.8)
                    Text("Toronto").font(.body).fontWeight(.thin).padding(.horizontal, 47.0).background(Color.black).frame(width: nil).opacity(0.8).foregroundColor(Color.white)
                }
            }
            ZStack(){
            Image("london")
                .resizable()
                .aspectRatio(contentMode: /*@START_MENU_TOKEN@*/.fit/*@END_MENU_TOKEN@*/)
                .frame(width: 330.0, height: 330.0)
                .cornerRadius(15.0)
    
                VStack(spacing:0){
                    Text("Big Ben").font(.title).foregroundColor(Color.white).padding(.horizontal, 28.0).padding(.vertical).background(Color.black).opacity(0.8)
                    Text("London").font(.body).fontWeight(.thin).padding(.horizontal, 46.3).background(Color.black).frame(width: nil).opacity(0.8).foregroundColor(Color.white)
                }
                .padding()
            }
        }
    }
}
struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
            .preferredColorScheme(.light)
    }
}

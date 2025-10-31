# 🏃‍♂️ Marathon Training Progressive Web App

Your complete 52-week marathon training companion with intelligent daily recommendations.

## 📦 What You Got

### 1. **marathon-trainer.html** - The Main App
A fully functional Progressive Web App that works on iPhone like a native app. Single HTML file with everything built in.

### 2. **marathon_training_program.docx** - Complete Training Guide  
Detailed 52-week training program document with:
- 4 training phases (Base Building, Endurance, Speed/Strength, Taper)
- Weekly schedules and mileage progressions
- Nutrition and hydration strategies
- Injury prevention exercises
- Race day preparation guide

### 3. **Documentation Files**
- `INSTALLATION_INSTRUCTIONS.md` - How to install the PWA on iPhone
- `HOSTING_GUIDE.md` - How to host the app online (free options)
- `app-preview.svg` - Visual guide showing app features

---

## 🚀 Quick Start

### For Immediate Use:
1. Open `marathon-trainer.html` in Safari on your iPhone
2. Tap Share → "Add to Home Screen"
3. Open the app from your home screen
4. Complete your first daily check-in

### For Best Experience:
1. Follow the `HOSTING_GUIDE.md` to put it online (5 minutes, free)
2. Access via URL on your iPhone
3. Add to Home Screen
4. Now you can access it anywhere!

---

## ✨ App Features

### 🎯 Daily Check-In System
Every morning, answer 5 quick questions:
- **Sleep Quality** (1-10): How well did you sleep?
- **Training Readiness** (1-10): How ready do you feel?
- **Resting Heart Rate**: Your morning HR (BPM)
- **Muscle Soreness** (1-10): Any aches or pains?
- **Motivation Level** (1-10): How motivated are you?

### 🤖 Intelligent Recommendations
Based on your check-in, the app provides:
- **🟢 Green**: You're ready! Proceed as planned
- **🟡 Yellow**: Reduce intensity 25-30%
- **🔴 Red**: Take it easy or rest

The algorithm analyzes your combined readiness score to prevent overtraining and injury.

### 📊 Progress Tracking
- Log completed workouts with actual distance
- Add notes about how you felt
- View total miles run
- See workouts completed
- Track progress through the 52 weeks

### 📅 52-Week Training Program
Built-in progressive training plan:
- **Weeks 1-13**: Base Building (15-28 miles/week)
- **Weeks 14-26**: Endurance Building (30-45 miles/week)
- **Weeks 27-39**: Speed & Strength (42-50 miles/week)
- **Weeks 40-52**: Taper & Race (45→26.2 miles)

### 💾 Smart Data Storage
- Everything stored locally on your device
- Works completely offline after installation
- No internet connection required
- Your data never leaves your phone
- No login, no tracking, no ads

---

## 📱 How the App Works

### Today Tab
- See your current week and phase
- Complete daily check-in
- Get personalized workout recommendation
- See adjusted distance based on readiness
- Log completed workouts

### Progress Tab
- View key statistics (week, workouts done, total miles)
- See your overall program progress
- Review current phase goals
- Track toward the 52-week finish line

### History Tab
- View all logged workouts (last 30 days)
- See workout notes and distances
- Adjust program start date if needed

---

## 🔧 Technical Details

### PWA Features
- **Installable**: Add to home screen like native app
- **Offline-First**: Works without internet
- **Responsive**: Optimized for mobile (especially iPhone)
- **Fast**: Loads instantly after first visit
- **Secure**: HTTPS not required for local files

### Technologies Used
- React 18 (via CDN)
- LocalStorage for data persistence
- Service Worker for offline capability
- Responsive CSS with native iOS feel

### Browser Support
- ✅ Safari (iOS) - Recommended
- ✅ Chrome (Android)
- ✅ Edge (Windows)
- ⚠️ Must use Safari on iPhone for "Add to Home Screen"

---

## 📖 Training Program Details

### Phase 1: Base Building (Weeks 1-13)
**Goal**: Build aerobic base and running consistency
- Increase frequency to 5 days/week
- Build from 5 to 12-mile long runs
- Weekly mileage: 15-28 miles
- Focus: Easy runs and cross-training

### Phase 2: Endurance Building (Weeks 14-26)
**Goal**: Extend long run capacity to 20 miles
- Add back-to-back long runs (Sat + Sun)
- Practice race nutrition/hydration
- Weekly mileage: 30-45 miles
- Focus: Building stamina

### Phase 3: Speed & Strength (Weeks 27-39)
**Goal**: Improve pace and running efficiency
- Add tempo runs and hill repeats
- Include marathon-pace segments
- Weekly mileage: 42-50 miles (peak)
- Focus: Speed work and strength

### Phase 4: Taper & Race (Weeks 40-52)
**Goal**: Arrive at race day fresh and ready
- Reduce volume, maintain intensity
- Final long runs by week 41
- Strategic taper to race week
- Week 52: Marathon! (26.2 miles)

---

## 🎓 How to Use Daily

### Morning Routine (5 minutes)
1. Open the app
2. Complete daily check-in
3. Review today's workout
4. Note the recommendation and distance

### After Workout (2 minutes)
1. Open the app
2. Tap "Mark Workout as Complete"
3. Enter actual distance
4. Add any notes (optional)
5. Complete!

### Weekly Review (10 minutes)
1. Check Progress tab
2. Review week's completed workouts
3. Compare to weekly target
4. Celebrate your progress!

---

## ⚙️ Customization

### Adjusting Start Date
If you didn't start November 1, 2025:
1. Go to History tab
2. Scroll to Settings section
3. Change "Program Start Date"
4. App recalculates current week automatically

### Understanding the Adjustment System

**Readiness Score Calculation:**
```
Score = (Sleep + Readiness + (10 - Soreness) + Motivation) / 4
```

**Intensity Adjustments:**
- Score < 5.0: Reduce to 50% (or rest)
- Score 5.0-6.5: Reduce to 70%
- Score 6.5-8.5: Proceed at 90%
- Score > 8.5: Full intensity (100%)

---

## 💡 Pro Tips

### For Best Results
1. **Be Honest**: Answer check-ins truthfully
2. **Be Consistent**: Check in every day
3. **Trust the System**: If it says rest, rest
4. **Log Everything**: Track all workouts
5. **Review Weekly**: Check your progress tab

### Preventing Injury
- Listen to 🔴 red warnings seriously
- Never ignore persistent pain
- Recovery weeks are essential
- Sleep is when you get stronger
- Nutrition matters as much as training

### Staying Motivated
- Set mini-goals (complete each week)
- Celebrate milestones (first 10-miler!)
- Review progress regularly
- Remember your "why"
- Join a running community

---

## 🏆 Training Philosophy

This app follows proven marathon training principles:

### The 10% Rule
Never increase weekly mileage by more than 10% to prevent injury.

### Progressive Overload
Gradually increase distance and intensity over 52 weeks.

### Recovery is Training
Built-in recovery weeks every 3-4 weeks (reduces volume 20-30%).

### Listen to Your Body
The app adjusts daily based on YOUR readiness, not a rigid plan.

### Sustainable Training
Focus on consistency over perfection. Missing one workout won't hurt; getting injured will.

---

## 📞 Support

### Troubleshooting

**Q: App not saving my data?**
A: Make sure you're using Safari and have storage space. Check Settings → Safari → Advanced.

**Q: Wrong week showing?**
A: Adjust start date in History tab → Settings.

**Q: Can't add to home screen?**
A: Must use Safari on iPhone. Chrome/Firefox won't work for iOS PWA installation.

**Q: App looks weird on Android?**
A: It's optimized for iOS but works on Android. Install via Chrome on Android.

**Q: Lost all my data?**
A: Data is stored per browser. If you cleared Safari data, it's gone. Always use the same browser.

### Best Practices

**Backup Your Data:**
While the app stores data locally, you can't export it (yet). Consider:
- Taking screenshots of your progress weekly
- Writing important notes elsewhere
- Using a running log app in parallel for backup

---

## 🎉 What's Next?

### After the Marathon
1. Take 2-4 weeks completely off running
2. Cross-train lightly (walk, swim, yoga)
3. Reflect on your journey
4. Set new goals
5. Maybe train for another? 😊

### Using the App for Future Races
- Adjust the start date for new training cycles
- The 52-week program can be used multiple times
- Each time you'll have the data from previous cycles

---

## 🏃 Ready to Begin?

**Today is Week 1, Day 1 of your marathon journey.**

1. ✅ Install the app (marathon-trainer.html)
2. ✅ Read the training document (marathon_training_program.docx)
3. ✅ Complete your first check-in
4. ✅ Do your first workout
5. ✅ Log it in the app

**52 weeks from now, you'll cross the marathon finish line.**

The hardest part is starting. You've got the tools. You've got the plan. Now trust the process and enjoy the journey!

---

## 📄 License & Credits

**Free to Use**: This app and training program are free forever. No ads, no tracking, no catches.

**Share It**: Feel free to share with friends training for marathons.

**Modify It**: The HTML file can be customized if you know coding.

---

**Remember**: Every marathon starts with a single step. You've taken yours by creating this training system. Now it's time to lace up those shoes and get started!

🏃‍♂️💪 Good luck with your training! 🎯🏆

---

*Created: October 31, 2025*
*Training Start: November 1, 2025*
*Race Day: October 31, 2026*
*Distance: 26.2 miles*
*You've got this!* ✨

// ==================== MIXED CHALLENGE 1 — STUDENT RESULT & ELIGIBILITY ====================

let obtainedMarks = 72;
let passingMarks = 40;
let attendance = 85;
let requiredAttendance = 75;

console.log(obtainedMarks >= passingMarks); // true
console.log(attendance >= requiredAttendance); // true
console.log(obtainedMarks >= passingMarks && attendance >= requiredAttendance); // true
console.log(obtainedMarks > 70 || attendance > 90); // true
console.log(attendance >= requiredAttendance); // true
console.log(obtainedMarks === passingMarks); // false


// ==================== MIXED CHALLENGE 2 — ONLINE SHOPPING WEBSITE ====================

let cartTotal = 5500;
let minimumOrder = 3000;
let walletBalance = 4000;
let premiumMember = true;

console.log(cartTotal >= minimumOrder); // true
console.log(walletBalance >= cartTotal); // false
console.log(cartTotal >= minimumOrder && walletBalance >= cartTotal); // false
console.log(premiumMember || cartTotal > 5000); // true
console.log(walletBalance >= cartTotal); // false
console.log(premiumMember === true); // true


// ==================== MIXED CHALLENGE 3 — GAMING PLATFORM ====================

let playerLevel = 18;
let requiredLevel = 15;
let coins = 1800;
let requiredCoins = 2000;
let premiumPass = true;

console.log(playerLevel >= requiredLevel); // true
console.log(coins >= requiredCoins); // false
console.log(playerLevel >= requiredLevel && coins >= requiredCoins); // false
console.log(premiumPass || playerLevel > 20); // true
console.log(requiredCoins > coins); // true
console.log(premiumPass !== false); // true


// ==================== MIXED CHALLENGE 4 — BANK ACCOUNT VERIFICATION ====================

let accountBalance = 50000;
let withdrawalAmount = 15000;
let pinVerified = true;
let dailyLimit = 20000;

console.log(withdrawalAmount <= dailyLimit); // true
console.log(accountBalance >= withdrawalAmount); // true
console.log(pinVerified && accountBalance >= withdrawalAmount); // true
console.log(accountBalance > 100000 || pinVerified); // true
console.log(withdrawalAmount < dailyLimit); // true
console.log(pinVerified === true); // true


// ==================== MIXED CHALLENGE 5 — EVENT REGISTRATION SYSTEM ====================

let age = 19;
let minimumAge = 18;
let registeredParticipants = 480;
let maximumParticipants = 500;
let vipInvite = false;

console.log(age >= minimumAge); // true
console.log(registeredParticipants < maximumParticipants); // true
console.log(age >= minimumAge && registeredParticipants < maximumParticipants); // true
console.log(vipInvite || age > 25); // false
console.log(registeredParticipants < maximumParticipants); // true
console.log(vipInvite !== true); // true


// ==================== MIXED CHALLENGE 6 — JOB APPLICATION PORTAL ====================

let experience = 3;
let requiredExperience = 2;
let degreeCompleted = true;
let referralAvailable = false;

console.log(experience >= requiredExperience); // true
console.log(degreeCompleted); // true
console.log(experience >= requiredExperience && degreeCompleted); // true
console.log(degreeCompleted || referralAvailable); // true
console.log(experience >= requiredExperience); // true
console.log(referralAvailable == true); // false


// ==================== MIXED CHALLENGE 7 — UNIVERSITY ADMISSION ====================

let testScore = 82;
let requiredScore = 75;
let documentsSubmitted = true;
let sportsQuota = false;

console.log(testScore >= requiredScore); // true
console.log(documentsSubmitted); // true
console.log(testScore >= requiredScore && documentsSubmitted); // true
console.log(sportsQuota || testScore > 90); // false
console.log(testScore >= requiredScore); // true
console.log(sportsQuota === false); // true

(this.webpackJsonpwatchmaker = this.webpackJsonpwatchmaker || []).push([
    [0], {
        12: function(e, t, n) {
            e.exports = {
                canvasCcontainer: "previewComponent_canvasCcontainer__xyfDu",
                canvasPreview: "previewComponent_canvasPreview__3pqS6"
            }
        },
        14: function(e, t, n) {
            e.exports = {
                json: "JsonComponent_json__GHlEn"
            }
        },
        20: function(e, t, n) {},
        22: function(e, t, n) {},
        24: function(e, t, n) {},
        25: function(e, t, n) {
            "use strict";
            n.r(t);
            var a = n(2),
                i = n.n(a),
                o = n(13),
                s = n.n(o),
                r = (n(20), n(5)),
                l = (n(21), n(26)),
                d = n(27),
                c = n(28),
                u = (n(22), n(30)),
                m = Object(a.createContext)(null),
                h = n(3),
                g = n(10),
                b = /^#[0-9A-F]{6}$/i,
                j = function() {
                    function e() {
                        Object(h.a)(this, e)
                    }
                    return Object(g.a)(e, null, [{
                        key: "hexToRgb",
                        value: function(e) {
                            var t = /^#?([a-f\d]{2})([a-f\d]{2})([a-f\d]{2})$/i.exec(e);
                            return t ? {
                                r: parseInt(t[1], 16),
                                g: parseInt(t[2], 16),
                                b: parseInt(t[3], 16)
                            } : null
                        }
                    }, {
                        key: "rgbToHex",
                        value: function(e, t, n) {
                            return "#" + e.toString(16).padStart(2, "0") + t.toString(16).padStart(2, "0") + n.toString(16).padStart(2, "0")
                        }
                    }, {
                        key: "colorRead",
                        value: function(e) {
                            return e ? (18 === e.length && (e = e.substring(0, 2) + e.substring(10, 18)), 10 === e.length && (e = "#" + e.substring(4)), e) : null
                        }
                    }, {
                        key: "colorBackgroundRead",
                        value: function(e) {
                            if (!e) return null;
                            18 === e.length && (e = e.substring(0, 2) + e.substring(8, 18));
                            var t, n, a, i = e.substring(8, 10),
                                o = e.substring(10, 12),
                                s = parseInt(i, 16),
                                r = parseInt(o, 16);
                            return t = (s >> 3 & 31) << 3, n = (r >> 5 & 7 | (7 & s) << 3) << 2, a = (31 & r) << 3, this.rgbToHex(t, n, a)
                        }
                    }, {
                        key: "colorBackgroundWrite",
                        value: function(e) {
                            var t = this.hexToRgb(e),
                                n = t.r,
                                a = t.g,
                                i = t.b >> 3 & 31 | (a >> 2 & 7) << 5;
                            return "0xFFFF" + (a >> 5 & 7 | (n >> 3 & 31) << 3).toString(16).padStart(2, "0").toUpperCase() + i.toString(16).padStart(2, "0").toUpperCase()
                        }
                    }, {
                        key: "colorWrite",
                        value: function(e) {
                            var t = this.hexToRgb(e),
                                n = t.r,
                                a = t.g,
                                i = t.b;
                            return "0xFF" + n.toString(16).padStart(2, "0") + a.toString(16).padStart(2, "0") + i.toString(16).padStart(2, "0")
                        }
                    }, {
                        key: "GFG_Fun",
                        value: function(e) {
                            return b.test(e)
                        }
                    }]), e
                }();
            j.DEFAULT_COLOR = "#000000";
            var p = function e(t, n) {
                    Object(h.a)(this, e), this.index = t, this.json = n
                },
                v = function() {
                    function e() {
                        Object(h.a)(this, e)
                    }
                    return Object(g.a)(e, null, [{
                        key: "toJson",
                        value: function(t) {
                            return void 0 === t ? this.Default.json : Object.values(e).find((function(e) {
                                return e.index === t
                            })).json
                        }
                    }, {
                        key: "fromJson",
                        value: function(t) {
                            return void 0 === t ? this.Default.index : Object.values(e).find((function(e) {
                                return e.json === t
                            })).index
                        }
                    }]), e
                }();
            v.Default = new p(0, "Default"), v.Left = new p(2, "Left"), v.Right = new p(4, "Right"), v.HCenter = new p(8, "HCenter"), v.Top = new p(16, "Top"), v.Bottom = new p(32, "Bottom"), v.VCenter = new p(64, "VCenter"), v.TopCenter = new p(v.Top.index | v.HCenter.index, "TopCenter"), v.TopLeft = new p(v.Top.index | v.Left.index, "TopLeft"), v.TopRight = new p(v.Top.index | v.Right.index, "TopRight"), v.Center = new p(v.VCenter.index | v.HCenter.index, "Center"), v.CenterLeft = new p(v.VCenter.index | v.Left.index, "CenterLeft"), v.CenterRight = new p(v.VCenter.index | v.Right.index, "CenterRight"), v.BottomCenter = new p(v.Bottom.index | v.HCenter.index, "BottomCenter"), v.BottomLeft = new p(v.Bottom.index | v.Left.index, "BottomLeft"), v.BottomRight = new p(v.Bottom.index | v.Right.index, "BottomRight");
            var f = function() {
                function e() {
                    Object(h.a)(this, e)
                }
                return Object(g.a)(e, null, [{
                    key: "findByIndex",
                    value: function(t) {
                        return void 0 === t ? this.Workout : Object.values(e).find((function(e) {
                            return e.index === t
                        }))
                    }
                }, {
                    key: "toJson",
                    value: function(t) {
                        return void 0 === t ? this.Workout.json : Object.values(e).find((function(e) {
                            return e.index === t
                        })).json
                    }
                }, {
                    key: "findByJson",
                    value: function(t) {
                        return void 0 === t ? this.Workout : Object.values(e).find((function(e) {
                            return e.json === t
                        }))
                    }
                }, {
                    key: "fromJson",
                    value: function(t) {
                        return void 0 === t ? this.Workout.index : Object.values(e).find((function(e) {
                            return e.json === t
                        })).index
                    }
                }]), e
            }();
            f.Workout = new p(5, "Workout"), f.CycleTracking = new p(10, "CycleTracking"), f.Music = new p(16, "Music"), f.Countdown = new p(17, "Countdown"), f.StopWatch = new p(18, "StopWatch"), f.Pomodoro = new p(19, "Pomodoro"), f.Voice = new p(25, "Voice");
            var x = function() {
                function e() {
                    Object(h.a)(this, e)
                }
                return Object(g.a)(e, null, [{
                    key: "findByIndex",
                    value: function(t) {
                        return void 0 === t ? this.Date : Object.values(e).find((function(e) {
                            return e.index === t
                        }))
                    }
                }, {
                    key: "toJson",
                    value: function(t) {
                        return void 0 === t ? this.Date.json : Object.values(e).find((function(e) {
                            return e.index === t
                        })).json
                    }
                }, {
                    key: "findByJson",
                    value: function(t) {
                        return void 0 === t ? this.Date : Object.values(e).find((function(e) {
                            return e.json === t
                        }))
                    }
                }, {
                    key: "fromJson",
                    value: function(t) {
                        return void 0 === t ? this.Date.index : Object.values(e).find((function(e) {
                            return e.json === t
                        })).index
                    }
                }]), e
            }();
            x.Date = new p(0, "Date"), x.Battery = new p(1, "Battery"), x.Steps = new p(2, "Steps"), x.Calories = new p(3, "Calories"), x.HeartRate = new p(4, "HeartRate"), x.Pai = new p(5, "PAI"), x.Distance = new p(6, "Distance"), x.StandUp = new p(7, "StandUp"), x.Weather = new p(8, "Weather"), x.UVindex = new p(9, "UVindex"), x.AirQuality = new p(10, "AirQuality"), x.Humidity = new p(11, "Humidity"), x.Sunrise = new p(12, "Sunrise"), x.WindForce = new p(13, "WindForce"), x.Altitude = new p(14, "Altitude"), x.AirPressure = new p(15, "AirPressure"), x.Stress = new p(16, "Stress"), x.ActivityGoal = new p(17, "ActivityGoal"), x.FatBurning = new p(18, "FatBurning");
            var O = function e() {
                    Object(h.a)(this, e), this.X = 0, this.Y = 0, this.ImageIndex = void 0
                },
                y = function e() {
                    Object(h.a)(this, e), this.X = 0, this.Y = 0, this.ImageIndex = void 0, this.ImagesCount = 1
                },
                I = function e() {
                    Object(h.a)(this, e), this.Unknown1 = void 0, this.TenThousands = void 0, this.Thousands = void 0, this.Hundreds = void 0, this.Tens = void 0, this.Ones = void 0, this.NoDataImage = void 0
                },
                w = function e() {
                    Object(h.a)(this, e), this.Unknown1 = 0, this.Thousands = void 0, this.Hundreds = void 0, this.Tens = void 0, this.Ones = void 0, this.NoDataImage = void 0
                },
                C = function e() {
                    Object(h.a)(this, e), this.Unknown1 = 0, this.Hundreds = void 0, this.Tens = void 0, this.Ones = void 0, this.NoDataImage = void 0
                },
                S = function e() {
                    Object(h.a)(this, e), this.Tens = void 0, this.Ones = void 0
                },
                D = function e() {
                    Object(h.a)(this, e), this.TopLeftX = 0, this.TopLeftY = 0, this.BottomRightX = 0, this.BottomRightY = 0, this.Alignment = v.TopLeft.json, this.Spacing = 0, this.VerticalOffset = 0, this.ImageIndex = void 0, this.ImagesCount = 1
                },
                N = function e() {
                    Object(h.a)(this, e), this.TopLeftX = 0, this.TopLeftY = 0, this.BottomRightX = 0, this.BottomRightY = 0, this.UnknownBoolean5 = !0
                },
                M = function e() {
                    Object(h.a)(this, e), this.X = 0, this.Y = 0
                },
                P = function e() {
                    Object(h.a)(this, e), this.CommonX = void 0, this.CommonY = void 0, this.ImageIndexAMCN = void 0, this.ImageIndexPMCN = void 0, this.AmImageIndexEN = void 0, this.PmImageIndexEN = void 0, this.CoordinatesAM = void 0, this.CoordinatesPM = void 0
                },
                T = function e() {
                    Object(h.a)(this, e), this.ImageIndex = void 0, this.Coordinates = []
                },
                k = function e() {
                    Object(h.a)(this, e), this.CenterX = 0, this.CenterY = 0, this.RadiusX = 0, this.RadiusY = 0, this.StartAngle = 0, this.EndAngle = 360, this.Width = 0, this.Color = void 0, this.Flatness = 0, this.ImageIndex = void 0
                },
                A = function e() {
                    Object(h.a)(this, e), this.CenterX = 0, this.CenterY = 0, this.RangeFrom = 0, this.RangeTo = 360, this.PointerImageIndex = void 0, this.PointerCenterOfRotationY = void 0
                },
                L = function e() {
                    Object(h.a)(this, e), this.Coordinates = new M, this.ImageIndexOn = void 0, this.ImageIndexOff = void 0
                },
                E = function e() {
                    Object(h.a)(this, e), this.Icon = void 0, this.ShortcutType = void 0, this.Element = void 0
                },
                Y = function e() {
                    Object(h.a)(this, e), this.ImageIndex = void 0, this.PointerCenterOfRotationY = void 0, this.CenterCoordinates = new M, this.CoverImage = void 0
                },
                H = function e() {
                    Object(h.a)(this, e), this.ImageProgress = new y, this.FrameInterval = void 0, this.PlayTimes = void 0, this.Repeat = void 0
                },
                U = {
                    count: 10,
                    numberLenght: 2,
                    title: "Hours",
                    timeDelimiter: !0,
                    displayAnalog: !1,
                    imageProgressTotal: 12
                },
                B = {
                    count: 10,
                    numberLenght: 2,
                    title: "Minutes",
                    imageProgressTotal: 60,
                    displayAnalog: !1,
                    timeDelimiter: !0
                },
                X = {
                    count: 10,
                    numberLenght: 2,
                    title: "Seconds",
                    timeDelimiter: !0,
                    displayAnalog: !1,
                    imageProgressTotal: 60
                },
                R = {
                    count: 10,
                    numberLenght: 4,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    title: "Year"
                },
                F = {
                    count: 10,
                    numberLenght: 2,
                    displayAnalog: !1,
                    imageProgressTotal: 12,
                    title: "Month"
                },
                W = {
                    count: 12,
                    numberLenght: 1,
                    displayAnalog: !0,
                    imageProgressTotal: 12,
                    title: "Month as word"
                },
                Z = {
                    count: 10,
                    numberLenght: 2,
                    displayAnalog: !1,
                    imageProgressTotal: 30,
                    title: "Day"
                },
                G = {
                    count: 7,
                    numberLenght: 1,
                    displayAnalog: !0,
                    imageProgressTotal: 7,
                    title: "Weekday"
                },
                J = {
                    count: 10,
                    numberLenght: 3,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    title: "Battery"
                },
                _ = {
                    count: 10,
                    numberLenght: 5,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    title: "Steps"
                },
                Q = {
                    count: 10,
                    numberLenght: 4,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    title: "Calories"
                },
                V = {
                    count: 10,
                    numberLenght: 3,
                    displayAnalog: !1,
                    imageProgressTotal: 6,
                    title: "Heart rate"
                },
                K = {
                    count: 10,
                    numberLenght: 3,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    title: "PAI"
                },
                z = {
                    count: 10,
                    numberLenght: 4,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    decimalDelimiter: !0,
                    title: "Distance"
                },
                $ = {
                    count: 10,
                    numberLenght: 2,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    title: "Standup"
                },
                q = {
                    count: 10,
                    numberLenght: 2,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    title: "UVIndex"
                },
                ee = {
                    count: 10,
                    numberLenght: 2,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    title: "Air quality"
                },
                te = {
                    count: 10,
                    numberLenght: 3,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    title: "Humidity"
                },
                ne = {
                    count: 10,
                    numberLenght: 4,
                    displayAnalog: !1,
                    imageProgressTotal: null,
                    timeDelimiter: !0,
                    title: "Sunrise"
                },
                ae = {
                    count: 10,
                    numberLenght: 2,
                    displayAnalog: !1,
                    imageProgressTotal: 26,
                    title: "Weather"
                },
                ie = function e(t, n) {
                    Object(h.a)(this, e), this.enabled = !1, this.json = new D, this.prefix = void 0, this.dataType = void 0, this.delimiter = void 0, this.delimiterCoords = new M, this.paddingZero = void 0, this.follow = void 0, this.con = void 0, t && (this.json = t, this.enabled = !0), n && (this.json || (this.json = new D), this.json.ImagesCount = n.count, this.con = n)
                },
                oe = function e(t) {
                    Object(h.a)(this, e), this.enabled = !1, this.json = new N, t && (this.enabled = !0, this.json = t)
                },
                se = function e(t) {
                    Object(h.a)(this, e), this.enabled = !1, this.watchNumber = new ie(null, ae), this.minus = void 0, this.suffix = void 0, this.nodata = void 0, this.shortcut = new oe, t && (this.enabled = !0, this.watchNumber = new ie(t.ImageNumber, ae), this.minus = t.MinusImageIndex, this.suffix = t.SuffixImageIndexC, this.nodata = t.NoDataImageIndex, this.shortcut = new oe(t.Shortcut))
                },
                re = function e(t, n) {
                    Object(h.a)(this, e), this.enabled = !1, this.json = new y, n ? (this.enabled = !0, this.json = n) : this.json.ImagesCount = t || 1
                },
                le = function e(t) {
                    Object(h.a)(this, e), this.enabled = !1, this.json = new O, t && (this.enabled = !0, this.json = t)
                },
                de = function e(t) {
                    Object(h.a)(this, e), this.enabled = !1, this.json = new T, t && (this.enabled = !0, this.json = t)
                },
                ce = function e(t) {
                    Object(h.a)(this, e), this.enabled = !1, this.json = new k, t && (this.enabled = !0, this.json = t)
                },
                ue = function e(t) {
                    Object(h.a)(this, e), this.enabled = !1, this.pointerScaleJson = new A, this.bottomImage = new le, t && (this.enabled = !0, this.pointerScaleJson = t.PointerScale, this.bottomImage = new le(t.BottomImage))
                },
                me = function e(t, n) {
                    Object(h.a)(this, e), this.imageProgress = new re(null), this.iconSetProgress = new de, this.circleScale = new ce, this.scale = new ue, this.noDataImage = new le, n && (this.imageProgress = new re(t, n.ImageProgress), this.iconSetProgress = new de(n.IconSetProgress), this.circleScale = new ce(n.CircleScale), this.scale = new ue(n.Scale), this.noDataImage = new le(n.NoDataImage))
                },
                he = function e(t) {
                    var n, a, i;
                    (Object(h.a)(this, e), this.collapsed = !0, this.collapsedAirQuality = !0, this.collapsedHumidity = !0, this.collapsedUvIndex = !0, this.airQualityNumber = new ie(null, ee), this.airQualityIcon = new le, this.humidityNumber = new ie(null, te), this.humiditySuffix = void 0, this.humidityIcon = new le, this.humidityProgress = new me(te.imageProgressTotal), this.uvNumber = new ie(null, q), this.uvSuffixImageIndex = void 0, this.uvShortcut = new oe, this.uvIcon = new le, this.uvProgress = new me(q.imageProgressTotal), t) && ((null === (n = t.Weather) || void 0 === n ? void 0 : n.AirQuality) && (this.airQualityNumber = new ie(t.Weather.AirQuality.AirQualityNumber, ee), this.airQualityIcon = new le(t.Weather.AirQuality.AirQualityIcon)), (null === (a = t.Weather) || void 0 === a ? void 0 : a.Humidity) && (this.humidityNumber = new ie(t.Weather.Humidity.HumidityNumber, te), this.humiditySuffix = t.Weather.Humidity.SuffixImageIndex, this.humidityIcon = new le(t.Weather.Humidity.HumidityIcon)), t.HumidityProgress && (this.humidityProgress = new me(te.imageProgressTotal, t.HumidityProgress)), (null === (i = t.Weather) || void 0 === i ? void 0 : i.UVindex) && (this.uvNumber = new ie(t.Weather.UVindex.UVindexNumber, q), this.uvSuffixImageIndex = t.Weather.UVindex.SuffixImageIndex, this.uvShortcut = new oe(t.Weather.UVindex.Shortcut), this.uvIcon = new le(t.Weather.UVindex.UVindexIcon)), t.UviProgress && (this.uvProgress = new me(q.imageProgressTotal, t.UviProgress)))
                },
                ge = function e(t) {
                    var n, a, i, o, s, r, l, d, c, u, m;
                    (Object(h.a)(this, e), this.collapsed = !0, this.icon = new re(ae.imageProgressTotal), this.current = new se, this.oneLineMinMax = new ie(null, ae), this.oneLineMinus = void 0, this.oneLineDelimiter = void 0, this.oneLineDegrees = void 0, this.lowest = new se, this.highest = new se, t) && (this.icon = new re(ae.imageProgressTotal, null === (n = t.Weather) || void 0 === n || null === (a = n.Icon) || void 0 === a ? void 0 : a.Images), this.current = new se(null === (i = t.Weather) || void 0 === i || null === (o = i.Temperature) || void 0 === o ? void 0 : o.Current), this.lowest = new se(null === (s = t.Weather) || void 0 === s || null === (r = s.Temperature) || void 0 === r ? void 0 : r.Lowest), this.highest = new se(null === (l = t.Weather) || void 0 === l || null === (d = l.Temperature) || void 0 === d ? void 0 : d.Highest), (null === (c = t.Weather) || void 0 === c || null === (u = c.Temperature) || void 0 === u || null === (m = u.OneLine) || void 0 === m ? void 0 : m.OneLineMinMax) && (this.oneLineMinMax = new ie(t.Weather.Temperature.OneLine.OneLineMinMax.Number, ae), this.oneLineMinus = t.Weather.Temperature.OneLine.OneLineMinMax.MinusImageIndex, this.oneLineDelimiter = t.Weather.Temperature.OneLine.OneLineMinMax.DelimiterImageIndex, this.oneLineDegrees = t.Weather.Temperature.OneLine.OneLineMinMax.DegreesImageIndex))
                },
                be = function e(t) {
                    Object(h.a)(this, e), this.enabled = !1, this.json = new Y, t && (this.json = t, this.enabled = !0)
                },
                je = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.commonCenterCoordinates = void 0, this.hours = new be, this.minutes = new be, t && (this.hours = new be(t.Hours), this.minutes = new be(t.Minutes), this.commonCenterCoordinates = t.CommonCenterCoordinates)
                },
                pe = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.hours = new ie(null, U), this.minutes = new ie(null, B), t && (this.hours = new ie(t.Hours, U), this.minutes = new ie(t.Minutes, B), this.hours && (this.hours.paddingZero = t.PaddingZeroHours), this.minutes && (this.minutes.paddingZero = t.PaddingZeroMinutes, this.minutes.follow = t.MinutesFollowHours))
                },
                ve = function e(t, n) {
                    Object(h.a)(this, e), this.json = new I, this.enabled = !1, n ? (this.enabled = !0, this.json = n) : t && (this.json.Unknown1 = t)
                },
                fe = function e(t, n) {
                    Object(h.a)(this, e), this.json = new w, this.enabled = !1, n ? (this.enabled = !0, this.json = n) : t && (this.json.Unknown1 = t)
                },
                xe = function e(t, n) {
                    Object(h.a)(this, e), this.json = new C, this.enabled = !1, n ? (this.enabled = !0, this.json = n) : t && (this.json.Unknown1 = t)
                },
                Oe = function e(t) {
                    Object(h.a)(this, e), this.json = new S, this.enabled = !1, t && (this.enabled = !0, this.json = t)
                },
                ye = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.hours = new Oe, this.minutes = new Oe, this.separator = new le, this.paddingZero = void 0, t && (this.hours = new Oe(t.Hours), this.minutes = new Oe(t.Minutes), this.separator = new le(t.Separator), this.paddingZero = t.PaddingZeroHours)
                },
                Ie = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.enabled = !1, this.json = new P, t && (this.enabled = !0, this.json = t)
                },
                we = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.timeSeparateDigits = new ye, this.timeAnalog = new je, this.amPm = new Ie, this.timeDigital = new pe, t && (this.timeSeparateDigits = new ye(t.TimeSeparateDigits), this.timeAnalog = new je(t.TimeAnalog), this.amPm = new Ie(t.AmPm), this.timeDigital = new pe(t.TimeDigital))
                },
                Ce = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.monthAndDay = new ie(null, F), this.separatorImageIndex = void 0, t && (this.monthAndDay = new ie(t.MonthAndDay, F), this.separatorImageIndex = t.SeparatorImageIndex)
                },
                Se = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.month = new ie(null, F), this.day = new ie(null, Z), t && (this.month = new ie(t.Month, F), this.day = new ie(t.Day, Z), this.month && (this.month.paddingZero = t.PaddingZeroMonth, this.month.dataType = t.MonthDataTypeImageIndex, this.month.delimiter = t.DelimiterMonthImageIndex, this.month.delimiterCoords = t.DelimiterMonthCoordinates), this.day && (this.day.paddingZero = t.PaddingZeroDay, this.day.dataType = t.DayDataTypeImageIndex, this.day.delimiter = t.DelimiterDayImageIndex, this.day.follow = !!t.DayFollowsMonth && t.DayFollowsMonth, this.day.delimiterCoords = t.DelimiterDayCoordinates))
                },
                De = function e(t, n) {
                    Object(h.a)(this, e), this.enabled = void 0, this.imageNumber = new ie(null, null), this.prefix = void 0, this.noData = void 0, this.icon = new le, this.shortcut = new oe, this.suffix = void 0, this.decimalPoint = void 0, this.suffixKM = void 0, this.suffixMI = void 0, this.suffixImageCoordinates = void 0, n ? (this.enabled = !0, this.imageNumber = new ie(n.ImageNumber, t), this.prefix = n.PrefixImageIndex, this.noData = n.NoDataImageIndex, this.icon = new le(n.Icon), this.shortcut = new oe(n.Shortcut), this.suffix = n.SuffixImageIndex, this.decimalPoint = n.DecimalPointImageIndex, this.suffixKM = n.SuffixKMImageIndex, this.suffixMI = n.SuffixMIImageIndex, this.suffixImageCoordinates = n.SuffixImageCoordinates) : t && (this.imageNumber = new ie(null, t))
                },
                Ne = function e(t, n, a) {
                    Object(h.a)(this, e), this.collapsed = !0, this.aElement = new De, this.aProgress = new me(null), this.con = void 0, n && (this.aElement = new De(t, n)), a && (this.aProgress = new me(t.imageProgressTotal, a)), this.aElement ? (this.aElement.imageNumber.con = t, this.aElement.imageNumber.json.ImagesCount = t.count) : this.aElement = new De(t), this.con = t
                },
                Me = function e(t) {
                    var n;
                    (Object(h.a)(this, e), this.collapsed = !0, this.time = new we, this.date = new Se, this.dateOneLine = new Ce, this.weekday = new re(G.imageProgressTotal), this.steps = new Ne(_), t) && (this.time = new we(t.TimeExtended), this.dateOneLine = new Ce(t.DateOneLine), this.weekday = new re(G.imageProgressTotal, null === (n = t.Week) || void 0 === n ? void 0 : n.Weekday), this.steps = new Ne(_, t.Steps), this.date = new Se(t.Date))
                },
                Pe = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.imageSetAnimation = [], t && t.ImageSetAnimation && (this.imageSetAnimation = t.ImageSetAnimation)
                },
                Te = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.text = new De(J), this.imageProgress = new re(J.imageProgressTotal), this.iconSetProgress = new de, this.scale = new ue, this.icon = new le, t && (t.BatteryText && (this.text = new De(J, t.BatteryText)), t.ImageProgress && (this.imageProgress = new re(J.imageProgressTotal, t.ImageProgress)), t.IconSetProgress && (this.iconSetProgress = new de(t.IconSetProgress)), t.Scale && (this.scale = new ue(t.Scale)), t.Icon && (this.icon = new le(t.Icon)))
                },
                ke = function e(t) {
                    Object(h.a)(this, e), this.enabled = !1, this.json = new L, t && (this.enabled = !0, this.json = t)
                },
                Ae = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.doNotDisturb = new ke, this.lock = new ke, this.bluetooth = new ke, this.alarm = new ke, t && (this.doNotDisturb = new ke(t.DoNotDisturb), this.lock = new ke(t.Lock), this.bluetooth = new ke(t.Bluetooth), this.alarm = new ke(t.Alarm))
                },
                Le = function e(t) {
                    var n, a, i, o, s, r, l, d, c, u, m, g;
                    (Object(h.a)(this, e), this.collapsed = !0, this.collapsedSeparated = !0, this.steps = new Ne(_), this.calories = new Ne(Q), this.heartRate = new Ne(V), this.distance = new Ne(z), this.pai = new Ne(K), this.standUp = new Ne($), this.caloriesSeparatedDigits = new fe(104), this.batterySeparatedDigits = new xe(101), this.stepsSeparatedDigits = new ve(103), this.heartRateSeparatedDigits = new xe(102), t) && (((null === (n = t.Activity) || void 0 === n ? void 0 : n.Steps) || t.StepProgress) && (this.steps = new Ne(_, null === (a = t.Activity) || void 0 === a ? void 0 : a.Steps, t.StepProgress)), ((null === (i = t.Activity) || void 0 === i ? void 0 : i.Calories) || t.CaloriesProgress) && (this.calories = new Ne(Q, null === (o = t.Activity) || void 0 === o ? void 0 : o.Calories, t.CaloriesProgress)), ((null === (s = t.Activity) || void 0 === s ? void 0 : s.HeartRate) || t.HeartProgress) && (this.heartRate = new Ne(V, null === (r = t.Activity) || void 0 === r ? void 0 : r.HeartRate, t.HeartProgress)), (null === (l = t.Activity) || void 0 === l ? void 0 : l.Distance) && (this.distance = new Ne(z, null === (d = t.Activity) || void 0 === d ? void 0 : d.Distance, null)), ((null === (c = t.Activity) || void 0 === c ? void 0 : c.PAI) || t.PaiProgress) && (this.pai = new Ne(K, null === (u = t.Activity) || void 0 === u ? void 0 : u.PAI, t.PaiProgress)), ((null === (m = t.Activity) || void 0 === m ? void 0 : m.StandUp) || t.StandUpProgress) && (this.standUp = new Ne($, null === (g = t.Activity) || void 0 === g ? void 0 : g.StandUp, t.StandUpProgress)), t.ActivitySeparateDigits && (this.stepsSeparatedDigits = new ve(103, t.ActivitySeparateDigits.Steps), this.batterySeparatedDigits = new xe(101, t.ActivitySeparateDigits.Battery), this.caloriesSeparatedDigits = new fe(104, t.ActivitySeparateDigits.Calories), this.heartRateSeparatedDigits = new xe(102, t.ActivitySeparateDigits.HeartRate)))
                },
                Ee = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.ampm = new Ie, this.weekday = new re(G.imageProgressTotal), this.weekdayProgress = new me(G.imageProgressTotal), this.year = new ie(null, R), this.month = new ie(null, F), this.monthAsWord = new re(W.imageProgressTotal), this.day = new ie(null, Z), this.oneLineYear = void 0, this.oneLineMonth = void 0, this.oneLineDelimiter = void 0, t && (this.ampm = new Ie(t.AmPm), this.weekday = new re(G.imageProgressTotal, t.Weekday), this.weekdayProgress = new me(G.imageProgressTotal, t.WeekdayProgress), t.Date && (t.Date.MonthAndDayAlt && (this.month = new ie(t.Date.MonthAndDayAlt.Month, F), this.monthAsWord = new re(W.imageProgressTotal, t.Date.MonthAndDayAlt.MonthName), this.day = new ie(t.Date.MonthAndDayAlt.Day, Z), this.month && (this.month.paddingZero = t.Date.PaddingZeroMonth), this.day && (this.day.paddingZero = t.Date.PaddingZeroDay)), t.Date.YearMonthAndDay && (this.year = new ie(t.Date.YearMonthAndDay.Year, R), this.month = new ie(t.Date.YearMonthAndDay.Month, F), this.monthAsWord = new re(W.imageProgressTotal, t.Date.YearMonthAndDay.MonthAsWord), this.day = new ie(t.Date.YearMonthAndDay.Day, Z), this.month && (this.month.delimiter = t.Date.YearMonthAndDay.DelimiterMonthImageIndex, this.month.follow = !!t.Date.YearMonthAndDay.MonthFollowsYear, this.month.dataType = t.Date.YearMonthAndDay.MonthDataTypeImageIndex, this.month.delimiterCoords = t.Date.YearMonthAndDay.DelimiterMonthCoordinates, this.month.paddingZero = t.Date.PaddingZeroMonth), this.day && (this.day.follow = !!t.Date.YearMonthAndDay.DayFollowsMonth, this.day.delimiter = t.Date.YearMonthAndDay.DelimiterDayImageIndex, this.day.dataType = t.Date.YearMonthAndDay.DayDataTypeImageIndex, this.day.delimiterCoords = t.Date.YearMonthAndDay.DelimiterDayCoordinates, this.day.paddingZero = t.Date.PaddingZeroDay), this.year && (this.year.delimiter = t.Date.YearMonthAndDay.DelimiterYearImageIndex, this.year.dataType = t.Date.YearMonthAndDay.YearDataTypeImageIndex, this.year.delimiterCoords = t.Date.YearMonthAndDay.DelimiterYearCoordinates, this.year.paddingZero = !0)), t.Date.OneLineMonthAndDay && (this.oneLineMonth = !0, this.month = new ie(t.Date.OneLineMonthAndDay.Number, F), this.month && (this.month.paddingZero = t.Date.PaddingZeroMonth), this.oneLineDelimiter = t.Date.OneLineMonthAndDay.DelimiterImageIndex), t.Date.OneLineYearMonthAndDay && (this.oneLineYear = !0, this.year = new ie(t.Date.OneLineYearMonthAndDay.Number, R), this.year && (this.year.paddingZero = !0), this.oneLineDelimiter = t.Date.OneLineYearMonthAndDay.DelimiterImageIndex)))
                },
                Ye = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.hours = new be, this.minutes = new be, this.seconds = new be, this.commonCenterCoordinates = void 0, t && (this.hours = new be(t.Hours), this.minutes = new be(t.Minutes), this.seconds = new be(t.Seconds), this.commonCenterCoordinates = t.CommonCenterCoordinates)
                },
                He = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.hours = new Oe, this.minutes = new Oe, this.seconds = new Oe, this.separatorHours = new le, this.separatorMinutes = new le, this.paddingZeroHours = !1, this.paddingZeroMinutes = !1, t && (this.hours = new Oe(t.Hours), this.minutes = new Oe(t.Minutes), this.seconds = new Oe(t.Seconds), this.separatorHours = new le(t.SeparatorHours), this.separatorMinutes = new le(t.SeparatorMinutes), this.paddingZeroHours = !!t.PaddingZeroHours, this.paddingZeroMinutes = !!t.PaddingZeroMinutes)
                },
                Ue = function e(t) {
                    if (Object(h.a)(this, e), this.collapsed = !0, this.hours = new ie(null, U), this.minutes = new ie(null, B), this.seconds = new ie(null, X), this.time_unknown1 = 0, t && (this.hours = new ie(t.Hours, U), this.hours && (this.hours.delimiter = t.DelimiterHoursImageIndex ? t.DelimiterHoursImageIndex : null, this.hours.paddingZero = !!t.PaddingZeroHours && t.PaddingZeroHours, this.hours.dataType = t.HoursDataTypeImageIndex ? t.HoursDataTypeImageIndex : null, this.hours.follow = !1), t.Time)) {
                        var n, a, i, o, s, r, l, d, c, u, m;
                        if (this.time_unknown1 = t.Time.Unknown1, this.hours && (this.hours.delimiterCoords = null === (n = t.Time) || void 0 === n ? void 0 : n.HoursDataTypeCoordinates), this.minutes = new ie(null === (a = t.Time) || void 0 === a ? void 0 : a.Minutes, B), this.minutes) this.minutes.delimiter = t.DelimiterMinutesImageIndex ? t.DelimiterMinutesImageIndex : null, this.minutes.paddingZero = !!(null === (o = t.Time) || void 0 === o ? void 0 : o.PaddingZeroMinutes), this.minutes.dataType = (null === (s = t.Time) || void 0 === s ? void 0 : s.MinutesDataTypeImageIndex) ? t.Time.MinutesDataTypeImageIndex : null, this.minutes.follow = !!(null === (r = t.Time) || void 0 === r ? void 0 : r.MinutesFollowHours), this.minutes.delimiterCoords = null === (l = t.Time) || void 0 === l ? void 0 : l.MinutesDataTypeCoordinates;
                        if (this.seconds = new ie(null === (i = t.Time) || void 0 === i ? void 0 : i.Seconds, X), this.seconds) this.seconds.delimiter = t.DelimiterSecondsImageIndex ? t.DelimiterSecondsImageIndex : null, this.seconds.dataType = (null === (d = t.Time) || void 0 === d ? void 0 : d.SecondsDataTypeImageIndex) ? t.Time.SecondsDataTypeImageIndex : null, this.seconds.paddingZero = !!(null === (c = t.Time) || void 0 === c ? void 0 : c.PaddingZeroSeconds), this.seconds.follow = !!(null === (u = t.Time) || void 0 === u ? void 0 : u.SecondsFollowMinutes), this.seconds.delimiterCoords = null === (m = t.Time) || void 0 === m ? void 0 : m.SecondsDataTypeCoordinates
                    }
                },
                Be = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.sunsetOneLine = new ie(null, ne), this.sunriseOneLine = new ie(null, ne), this.sunsetIcon = new le, this.sunsetShortcut = new oe, this.sunriseIcon = new le, this.sunriseShortcut = new oe, t && (this.sunsetOneLine = new ie(t.SunsetTimeOneLine, ne), this.sunriseOneLine = new ie(t.SunriseTimeOneLine, ne), this.sunsetOneLine && (this.sunsetOneLine.delimiter = t.DelimiterSunsetImageIndex, this.sunsetOneLine.prefix = t.SunsetImageIndex), this.sunriseOneLine && (this.sunriseOneLine.delimiter = t.DelimiterSunriseImageIndex, this.sunriseOneLine.prefix = t.SunriseImageIndex), this.sunsetIcon = new le(t.SunsetIcon), this.sunriseIcon = new le(t.SunriseIcon), this.sunsetShortcut = new oe(t.SunsetShortcut), this.sunriseShortcut = new oe(t.SunriseShortcut))
                },
                Xe = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.hours = new ie(null, U), this.minutes = new ie(null, B), t && (this.hours = new ie(t.Hours, U), this.minutes = new ie(t.Minutes, B), this.hours && (this.hours.dataType = t.DataTypeHoursImageIndex, this.hours.delimiter = t.DelimiterHoursImageIndex, this.hours.paddingZero = !!t.PaddingZeroHours, this.hours.delimiterCoords = t.DataTypeHoursCoordinates), this.minutes && (this.minutes.delimiter = t.DelimiterMinutesImageIndex, this.minutes.paddingZero = !!t.PaddingZeroMinutes, this.minutes.follow = !!t.MinutesFollowHours))
                },
                Re = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.noAlarm = new le, this.alarmImage = new le, this.shortcut = new oe, this.alarmTime = new Xe, t && (this.noAlarm = new le(t.NoAlarmImage), this.alarmImage = new le(t.AlarmImage), this.shortcut = new oe(t.ShortcutArea), this.alarmTime = new Xe(t.AlarmTime))
                },
                Fe = function e(t) {
                    var n;
                    (Object(h.a)(this, e), this.collapsed = !0, this.sunset = new Be, this.timeAnalog = new Ye, this.timeDigitalCommon = new Ue, this.timeDigitalSeparated = new He, this.alarm = new Re, t) && (this.alarm = new Re(t.Alarm), this.sunset = new Be(t.TimeExtended), this.timeAnalog = new Ye(t.TimeAnalog), this.timeDigitalCommon = new Ue(t.TimeDigital), this.timeDigitalSeparated = new He(null === (n = t.TimeExtended) || void 0 === n ? void 0 : n.TimeSeparateDigits))
                },
                We = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.image = new le, this.preview = new le, this.previewc = new le, this.previewtradchin = new le, this.floatingLayer = new le, this.color = j.DEFAULT_COLOR, t && (this.image = new le(t.Image), this.preview = new le(t.Preview), this.previewc = new le(t.PreviewChinese), this.previewtradchin = new le(t.PreviewTradChinese), this.floatingLayer = new le(t.FloatingLayer), this.color = j.colorRead(t.BackgroundColor))
                },
                Ze = function e(t) {
                    Object(h.a)(this, e), this.collapsed = !0, this.json = [], t && (this.json = t.Shortcut)
                },
                Ge = function e(t) {
                    Object(h.a)(this, e), this.background = new We, this.time = new Fe, this.activity = new Le, this.date = new Ee, this.status = new Ae, this.battery = new Te, this.animation = new Pe, this.weather = new ge, this.weatherext = new he, this.shortcuts = new Ze, this.aod = new Me, t && (this.background = new We(t.Background), this.time = new Fe(t), this.date = new Ee(t.DateBlock), this.activity = new Le(t), this.status = new Ae(t.Status), this.battery = new Te(t.Battery), this.aod = new Me(t.AlwaysOnDisplay), this.animation = new Pe(t.Animation), this.weather = new ge(t), this.weatherext = new he(t), this.shortcuts = new Ze(t.Shortcuts))
                },
                Je = function e() {
                    Object(h.a)(this, e)
                };
            Je.version = "1.5.0", Je.DEVICE_KEY = "com.kontranik.gts2editor.device", Je.NONE = "None", Je.startImageIndex = 0, Je.default_device_id = 73, Je.devices = {
                gts2minie: {
                    width: 306,
                    height: 354,
                    deviceId: 73,
                    title: "Gts2 mini"
                },
                bipu: {
                    width: 302,
                    height: 320,
                    deviceId: 71,
                    title: "Bip U"
                },
				bip3: {
                    width: 240,
                    height: 280,
                    deviceId: 74,
                    title: "Bip 3"
                }
            };
            var _e, Qe = n(0),
                Ve = function() {
                    var e = Object(a.useContext)(m),
                        t = e.images,
                        n = e.setImages,
                        i = e.setWatchface,
                        o = e.setJsonName;

                    function s(e) {
                        var t = e.target.result,
                            n = JSON.parse(t.toString()),
                            a = new Ge(n);
                        i(a)
                    }

                    function r(e, t) {
                        var n = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : 0;
                        if (n < e.length) {
                            var a = e[n].name,
                                i = a; - 1 !== i.lastIndexOf(".") && (i = i.substring(0, i.lastIndexOf(".")));
                            var o = parseInt(i);
                            if (/^\d+$/.test(i) && !isNaN(o)) {
                                var s = new Image;
                                s.addEventListener("load", (function() {
                                    (n += 1) < e.length ? r(e, t, n) : l(t)
                                })), s.src = URL.createObjectURL(e[n]), s.alt = a, t.push({
                                    id: o,
                                    name: a,
                                    image: s
                                })
                            } else(n += 1) < e.length ? r(e, t, n) : l(t)
                        }
                    }

                    function l(e) {
                        var t = e.sort((function(e, t) {
                            return e.id - t.id
                        }));
                        t[t.length - 1].id !== t.length - 1 + Je.startImageIndex && (console.log(t.length - 1 + Je.startImageIndex, t[t.length - 1].id), window.alert("Images files go out of order or some of the files are missing. Name the PNG files in ascending order.")), t[0].id !== Je.startImageIndex && window.alert("Images file numbering must start at ".concat(Je.startImageIndex, ".")), n(t)
                    }
                    return Object(Qe.jsx)("div", {
                        children: Object(Qe.jsxs)("span", {
                            className: "input-group input-group-sm mb-3",
                            children: [Object(Qe.jsx)("span", {
                                className: "input-group-text",
                                children: "Load images"
                            }), Object(Qe.jsx)("input", {
                                type: "file",
                                multiple: !0,
                                id: "fileUpload",
                                accept: "image/*",
                                onChange: function(e) {
                                    r(e.target.files, [])
                                }
                            }), t.length > 0 ? Object(Qe.jsxs)(Qe.Fragment, {
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Load json file"
                                }), Object(Qe.jsx)("input", {
                                    type: "file",
                                    accept: "application/json",
                                    id: "jsonLoad",
                                    onChange: function(e) {
                                        var t = e.target.files.item(0);
                                        if (t) {
                                            var n = new FileReader;
                                            n.onload = s, n.readAsText(t), o(e.target.files.item(0).name)
                                        }
                                    }
                                }), Object(Qe.jsx)(u.a, {
                                    onClick: function() {
                                        document.getElementById("jsonLoad") && (document.getElementById("jsonLoad").value = null), i(new Ge)
                                    },
                                    children: "clear"
                                })]
                            }) : ""]
                        })
                    })
                },
                Ke = n(1),
                ze = n(29);
            ! function(e) {
                e[e.Button = 0] = "Button", e[e.Checkbox = 1] = "Checkbox", e[e.Color = 2] = "Color", e[e.Date = 3] = "Date", e[e.Empty = 4] = "Empty", e[e.Number = 5] = "Number", e[e.Select = 6] = "Select", e[e.SelectFile = 7] = "SelectFile", e[e.Time = 8] = "Time"
            }(_e || (_e = {}));
            var $e = [{
                    value: "TopLeft",
                    title: "TopLeft"
                }, {
                    value: "TopCenter",
                    title: "TopCenter"
                }, {
                    value: "TopRight",
                    title: "TopRight"
                }, {
                    value: "CenterLeft",
                    title: "CenterLeft"
                }, {
                    value: "Center",
                    title: "Center"
                }, {
                    value: "CenterRight",
                    title: "CenterRight"
                }, {
                    value: "BottomLeft",
                    title: "BottomLeft"
                }, {
                    value: "BottomCenter",
                    title: "BottomCenter"
                }, {
                    value: "BottomRight",
                    title: "BottomRight"
                }],
                qe = [{
                    value: "0",
                    title: "Flat"
                }, {
                    value: "180",
                    title: "Round"
                }],
                et = (n(24), function(e) {
                    var t = e.title,
                        n = e.value,
                        i = e.onChange,
                        o = Object(a.useContext)(m).images,
                        s = Object(a.useState)(!0),
                        l = Object(r.a)(s, 2),
                        d = l[0],
                        c = l[1];

                    function u(e) {
                        i(e), c(!0)
                    }
                    var h = [];
                    if (h.push(Object(Qe.jsx)("option", {
                            value: "None",
                            children: " "
                        }, "None")), o)
                        for (var g = function() {
                                var e = o[b];
                                h.push(Object(Qe.jsxs)("li", {
                                    value: e.id,
                                    className: "list-group-item fileitem",
                                    onClick: function() {
                                        return u(e.id)
                                    },
                                    children: [Object(Qe.jsx)("img", {
                                        src: e.image.src,
                                        alt: e.name,
                                        width: 30
                                    }), e.name]
                                }, e.id))
                            }, b = 0; b < o.length; b++) g();
                    return Object(Qe.jsxs)(Qe.Fragment, {
                        children: [Object(Qe.jsx)("span", {
                            className: "input-group-text",
                            children: t
                        }), Object(Qe.jsxs)("div", {
                            className: "input-group-text dropdown",
                            children: [Object(Qe.jsx)("div", {
                                children: null !== n && void 0 !== n && o[n - Je.startImageIndex] ? o[n - Je.startImageIndex].name : "None"
                            }), d ? "" : Object(Qe.jsx)("ul", {
                                className: "list-group dropdown-content",
                                children: h
                            })]
                        }), Object(Qe.jsx)("button", {
                            className: "btn btn-outline-secondary",
                            type: "button",
                            onClick: function() {
                                c(!d)
                            },
                            disabled: !o || 0 === o.length,
                            children: "+"
                        }), Object(Qe.jsx)("button", {
                            className: "btn btn-outline-secondary",
                            type: "button",
                            onClick: function() {
                                u(null)
                            },
                            disabled: !(n >= 0),
                            children: "x"
                        })]
                    })
                }),
                tt = function(e) {
                    var t = e.title,
                        n = e.onClick,
                        a = e.disabled,
                        i = e.className;
                    return Object(Qe.jsx)(Qe.Fragment, {
                        children: Object(Qe.jsx)("button", {
                            className: "btn ".concat(i),
                            type: "button",
                            onClick: n,
                            disabled: a,
                            children: t
                        })
                    })
                },
                nt = function(e) {
                    var t = e.title,
                        n = e.checked,
                        a = e.onChange,
                        i = e.disabled;
                    return Object(Qe.jsxs)(Qe.Fragment, {
                        children: [Object(Qe.jsx)("span", {
                            className: "input-group-text",
                            id: "addon-wrapping",
                            children: t
                        }), Object(Qe.jsx)("div", {
                            className: "input-group-text",
                            children: Object(Qe.jsx)("input", {
                                className: "form-check-input form-check-input-sm",
                                type: "checkbox",
                                disabled: i,
                                checked: !!n,
                                onChange: function(e) {
                                    function t() {
                                        return e.apply(this, arguments)
                                    }
                                    return t.toString = function() {
                                        return e.toString()
                                    }, t
                                }((function() {
                                    return a(!n)
                                }))
                            })
                        })]
                    })
                },
                at = function(e) {
                    var t = e.title,
                        n = e.value,
                        a = e.onChange;
                    return Object(Qe.jsxs)(Qe.Fragment, {
                        children: [Object(Qe.jsx)("span", {
                            className: "input-group-text",
                            children: t
                        }), Object(Qe.jsx)("input", {
                            type: "color",
                            className: "form-control form-control-sm",
                            onChange: function(e) {
                                function t(t) {
                                    return e.apply(this, arguments)
                                }
                                return t.toString = function() {
                                    return e.toString()
                                }, t
                            }((function(e) {
                                a(e.target.value)
                            })),
                            id: "colorBackground",
                            value: n,
                            title: "Choose color"
                        })]
                    })
                },
                it = function(e) {
                    var t = e.title,
                        n = e.value,
                        a = e.onChange,
                        i = e.disabled,
                        o = e.min,
                        s = e.max;
                    return Object(Qe.jsxs)(Qe.Fragment, {
                        children: [Object(Qe.jsx)("span", {
                            className: "input-group-text",
                            id: "addon-wrapping",
                            children: t
                        }), Object(Qe.jsx)("input", {
                            type: "number",
                            className: "form-control form-control-sm",
                            value: n || 0,
                            min: o,
                            max: s,
                            onChange: function(e) {
                                function t(t) {
                                    return e.apply(this, arguments)
                                }
                                return t.toString = function() {
                                    return e.toString()
                                }, t
                            }((function(e) {
                                var t = parseInt(e.target.value);
                                a(isNaN(t) ? 0 : t)
                            })),
                            disabled: i
                        })]
                    })
                },
                ot = function(e) {
                    var t = e.title,
                        n = e.value,
                        a = e.onChange,
                        i = e.disabled,
                        o = e.options;
                    return Object(Qe.jsxs)(Qe.Fragment, {
                        children: [Object(Qe.jsx)("span", {
                            className: "input-group-text",
                            children: t
                        }), Object(Qe.jsx)("select", {
                            disabled: i,
                            value: n,
                            className: "form-select form-select-sm",
                            onChange: function(e) {
                                function t(t) {
                                    return e.apply(this, arguments)
                                }
                                return t.toString = function() {
                                    return e.toString()
                                }, t
                            }((function(e) {
                                return a(e.target.value)
                            })),
                            children: o.map((function(e) {
                                return Object(Qe.jsx)("option", {
                                    value: e.value,
                                    children: e.title
                                }, e.value)
                            }))
                        })]
                    })
                },
                st = function(e) {
                    var t = e.row;
                    return Object(Qe.jsx)(Qe.Fragment, {
                        children: Object(Qe.jsxs)("div", {
                            className: "input-group input-group-sm d-flex ".concat(t.showDelete ? "justify-content-between" : ""),
                            children: [t.blocks.map((function(e, t) {
                                return function(e, t) {
                                    var n = "";
                                    switch (e.type) {
                                        case _e.Empty:
                                            n = Object(Qe.jsx)("span", {
                                                className: "input-group-text",
                                                children: e.title
                                            }, t);
                                            break;
                                        case _e.SelectFile:
                                            n = Object(Qe.jsx)(et, {
                                                title: e.title,
                                                onChange: e.onChange,
                                                value: e.nvalue
                                            }, t);
                                            break;
                                        case _e.Number:
                                            n = Object(Qe.jsx)(it, {
                                                title: e.title,
                                                onChange: e.onChange,
                                                value: e.nvalue,
                                                disabled: e.disabled
                                            }, t);
                                            break;
                                        case _e.Checkbox:
                                            n = Object(Qe.jsx)(nt, {
                                                title: e.title,
                                                onChange: e.onChange,
                                                checked: e.checked,
                                                disabled: e.disabled
                                            }, t);
                                            break;
                                        case _e.Select:
                                            n = Object(Qe.jsx)(ot, {
                                                title: e.title,
                                                onChange: e.onChange,
                                                value: e.svalue,
                                                disabled: e.disabled,
                                                options: e.selectOptions
                                            }, t);
                                            break;
                                        case _e.Color:
                                            n = Object(Qe.jsx)(at, {
                                                title: e.title,
                                                onChange: e.onChange,
                                                value: e.svalue
                                            }, t);
                                            break;
                                        case _e.Button:
                                            n = Object(Qe.jsx)(tt, {
                                                title: e.title,
                                                onClick: e.onClick,
                                                className: e.className,
                                                disabled: e.disabled
                                            }, t)
                                    }
                                    return n
                                }(e, t)
                            })), t.showDelete ? Object(Qe.jsx)("button", {
                                className: "btn btn-outline-danger",
                                type: "button",
                                onClick: t.onDelete,
                                disabled: !t.onDelete,
                                children: "Delete"
                            }) : ""]
                        })
                    })
                },
                rt = function(e) {
                    var t = e.ar;
                    return Object(Qe.jsx)(Qe.Fragment, {
                        children: t.map((function(e, t) {
                            return e.disabled ? "" : Object(Qe.jsx)(st, {
                                row: e
                            }, t)
                        }))
                    })
                },
                lt = function(e) {
                    var t = e.title,
                        n = e.image,
                        i = e.onUpdate,
                        o = Object(a.useMemo)((function() {
                            return [{
                                blocks: [{
                                    title: "Image",
                                    type: _e.SelectFile,
                                    nvalue: n.json.ImageIndex,
                                    onChange: s
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: Math.round((78.46 / 100) * n.json.X),
                                    onChange: r
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: Math.round((78.46 / 100) * n.json.Y),
                                    onChange: l
                                }]
                            }]
                        }), [n]);

                    function s(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.ImageIndex = e, i(t)
                    }

                    function r(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.X = e, i(t)
                    }

                    function l(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.Y = e, i(t)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, n);
                                            e.enabled = !e.enabled, i(e)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsx)(ze.a.Body, {
                            children: Object(Qe.jsx)(rt, {
                                ar: o
                            })
                        }) : ""]
                    })
                },
                dt = function(e) {
                    var t = e.title,
                        n = e.digit,
                        i = e.onUpdate,
                        o = e.followDisabled,
                        s = (e.onCopyFromNormal, e.showDelimiter),
                        r = e.showDataType,
                        l = e.showPrefix,
                        d = e.paddingDisabled,
                        c = Object(a.useMemo)((function() {
                            var e, t, a, i, c, S, D;
                            return [{
                                blocks: [{
                                    title: "Image",
                                    type: _e.SelectFile,
                                    nvalue: null === (e = n.json) || void 0 === e ? void 0 : e.ImageIndex,
                                    onChange: g
                                }, {
                                    title: "Count: ".concat(null === (t = n.json) || void 0 === t ? void 0 : t.ImagesCount),
                                    type: _e.Empty
                                }]
                            }, {
                                blocks: [{
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: n.json.TopLeftX ? Math.round((78.46 / 100) * n.json.TopLeftX) : 0,
                                    onChange: b
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: n.json.TopLeftY ? Math.round((78.46 / 100) * n.json.TopLeftY) : 0,
                                    onChange: j
                                }]
                            }, {
                                blocks: [{
                                    title: "Bottom Right X",
                                    type: _e.Number,
                                    nvalue: n.json.BottomRightX ? Math.round((78.46 / 100) * n.json.BottomRightX) : 0,
                                    onChange: p
                                }, {
                                    title: "Bottom Right Y",
                                    type: _e.Number,
                                    nvalue: n.json.BottomRightY ? Math.round((78.46 / 100) * n.json.BottomRightY) : 0,
                                    onChange: v
                                }]
                            }, {
                                blocks: [{
                                    title: "padding zero",
                                    type: _e.Checkbox,
                                    checked: n.paddingZero,
                                    onChange: u,
                                    disabled: d
                                }, {
                                    title: "spacing",
                                    type: _e.Number,
                                    nvalue: (null === (a = n.json) || void 0 === a ? void 0 : a.Spacing) ? n.json.Spacing : 0,
                                    onChange: x
                                }, {
                                    title: "vertical offset",
                                    type: _e.Number,
                                    nvalue: (null === (i = n.json) || void 0 === i ? void 0 : i.VerticalOffset) ? n.json.VerticalOffset : 0,
                                    onChange: O
                                }]
                            }, {
                                blocks: [{
                                    title: "follow",
                                    type: _e.Checkbox,
                                    checked: n.follow,
                                    onChange: C,
                                    disabled: o
                                }, {
                                    title: "alignment",
                                    type: _e.Select,
                                    svalue: null === (c = n.json) || void 0 === c ? void 0 : c.Alignment,
                                    selectOptions: $e,
                                    onChange: f
                                }]
                            }, {
                                disabled: !l,
                                blocks: [{
                                    title: "Prefix",
                                    type: _e.SelectFile,
                                    nvalue: n.prefix,
                                    onChange: w
                                }]
                            }, {
                                disabled: !r,
                                blocks: [{
                                    title: "Data Type",
                                    type: _e.SelectFile,
                                    nvalue: n.dataType,
                                    onChange: I
                                }]
                            }, {
                                disabled: !s,
                                blocks: [{
                                    title: "Delimiter",
                                    type: _e.SelectFile,
                                    nvalue: n.delimiter,
                                    onChange: y
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (S = n.delimiterCoords) || void 0 === S ? void 0 : S.X) ? n.delimiterCoords.X : 0,
                                    onChange: m
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (D = n.delimiterCoords) || void 0 === D ? void 0 : D.Y) ? n.delimiterCoords.Y : 0,
                                    onChange: h
                                }]
                            }]
                        }), [n]);

                    function u(e) {
                        var t = Object(Ke.a)({}, n);
                        t.paddingZero = e, i(t)
                    }

                    function m(e) {
                        var t = Object(Ke.a)({}, n);
                        t.delimiterCoords || (t.delimiterCoords = new M), t.delimiterCoords.X = e, i(t)
                    }

                    function h(e) {
                        var t = Object(Ke.a)({}, n);
                        t.delimiterCoords || (t.delimiterCoords = new M), t.delimiterCoords.Y = e, i(t)
                    }

                    function g(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.ImageIndex = e, i(t)
                    }

                    function b(e) {
                        var t = Object(Ke.a)({}, n),
                            a = t.json.BottomRightX && t.json.TopLeftX ? t.json.BottomRightX - t.json.TopLeftX : 1;
                        t.json.TopLeftX = e, t.json.BottomRightX = e + a, i(t)
                    }

                    function j(e) {
                        var t = Object(Ke.a)({}, n),
                            a = t.json.BottomRightY && t.json.TopLeftY ? t.json.BottomRightY - t.json.TopLeftY : 1;
                        t.json.TopLeftY = e, t.json.BottomRightY = e + a, i(t)
                    }

                    function p(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.BottomRightX = e, i(t)
                    }

                    function v(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.BottomRightY = e, i(t)
                    }

                    function f(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.Alignment = e, i(t)
                    }

                    function x(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.Spacing = e, i(t)
                    }

                    function O(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.VerticalOffset = e, i(t)
                    }

                    function y(e) {
                        var t = Object(Ke.a)({}, n);
                        t.delimiter = e, i(t)
                    }

                    function I(e) {
                        var t = Object(Ke.a)({}, n);
                        t.dataType = e, i(t)
                    }

                    function w(e) {
                        var t = Object(Ke.a)({}, n);
                        t.prefix = e, i(t)
                    }

                    function C(e) {
                        var t = Object(Ke.a)({}, n);
                        t.follow = e, i(t)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, n);
                                            e.enabled = !e.enabled, i(e)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsx)(ze.a.Body, {
                            children: Object(Qe.jsx)(rt, {
                                ar: c
                            })
                        }) : ""]
                    })
                },
                ct = function(e) {
                    var t = e.title,
                        n = e.scale,
                        i = e.onUpdate,
                        o = Object(a.useMemo)((function() {
                            var e, t, a, i, o, b, p, v;
                            return [{
                                blocks: [{
                                    title: "Color",
                                    type: _e.Color,
                                    svalue: j.colorRead(null === (e = n.json) || void 0 === e ? void 0 : e.Color),
                                    onChange: s
                                }, {
                                    title: "Image",
                                    type: _e.SelectFile,
                                    nvalue: null === (t = n.json) || void 0 === t ? void 0 : t.ImageIndex,
                                    onChange: r
                                }]
                            }, {
                                blocks: [{
                                    title: "Center",
                                    type: _e.Empty
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (a = n.json) || void 0 === a ? void 0 : a.CenterX) ? Math.round((78.46 / 100) * n.json.CenterX) : 0,
                                    onChange: l
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (i = n.json) || void 0 === i ? void 0 : i.CenterY) ? Math.round((78.46 / 100) * n.json.CenterY) : 0,
                                    onChange: d
                                }]
                            }, {
                                blocks: [{
                                    title: "Start angle",
                                    type: _e.Number,
                                    nvalue: (null === (o = n.json) || void 0 === o ? void 0 : o.StartAngle) ? n.json.StartAngle : 0,
                                    onChange: c
                                }, {
                                    title: "End angle",
                                    type: _e.Number,
                                    nvalue: (null === (b = n.json) || void 0 === b ? void 0 : b.EndAngle) ? n.json.EndAngle : 360,
                                    onChange: u
                                }]
                            }, {
                                blocks: [{
                                    title: "Radius",
                                    type: _e.Number,
                                    nvalue: (null === (p = n.json) || void 0 === p ? void 0 : p.RadiusX) ? n.json.RadiusX : 0,
                                    onChange: m
                                }, {
                                    title: "Width",
                                    type: _e.Number,
                                    nvalue: (null === (v = n.json) || void 0 === v ? void 0 : v.Width) ? n.json.Width : 1,
                                    onChange: h
                                }]
                            }, {
                                blocks: [{
                                    title: "Line ending",
                                    type: _e.Select,
                                    svalue: n.json.Flatness ? n.json.Flatness.toString() : "0",
                                    onChange: g,
                                    selectOptions: qe
                                }]
                            }]
                        }), [n]);

                    function s(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.Color = j.colorWrite(e), i(t)
                    }

                    function r(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.ImageIndex = e, i(t)
                    }

                    function l(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CenterX = e, i(t)
                    }

                    function d(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CenterY = e, i(t)
                    }

                    function c(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.StartAngle = e, i(t)
                    }

                    function u(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.EndAngle = e, i(t)
                    }

                    function m(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.RadiusX = e, t.json.RadiusY = e, i(t)
                    }

                    function h(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.Width = e, i(t)
                    }

                    function g(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.Flatness = parseInt(e), i(t)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function(e) {
                                            var t = Object(Ke.a)({}, n);
                                            t.enabled = !t.enabled, t.enabled && !t.json && (t.json = new k), i(t)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsx)(ze.a.Body, {
                            children: Object(Qe.jsx)(rt, {
                                ar: o
                            })
                        }) : ""]
                    })
                },
                ut = function(e) {
                    var t = e.title,
                        n = e.iconSet,
                        i = e.onUpdate,
                        o = Object(a.useMemo)((function() {
                            return [{
                                blocks: [{
                                    title: "Image",
                                    type: _e.SelectFile,
                                    nvalue: n.json.ImageIndex,
                                    onChange: s
                                }, {
                                    title: "Add coordinates",
                                    type: _e.Button,
                                    onClick: r,
                                    className: "btn-outline-success"
                                }]
                            }]
                        }), [n]);

                    function s(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.ImageIndex = e, i(t)
                    }

                    function r() {
                        var e = Object(Ke.a)({}, n);
                        e.json.Coordinates || (e.json.Coordinates = []);
                        var t = e.json.Coordinates[e.json.Coordinates.length - 1];
                        e.json.Coordinates.push({
                            X: t ? t.X : 0,
                            Y: t ? t.Y : 0
                        }), i(e)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, n);
                                            e.json.Coordinates || (e.json.Coordinates = [{
                                                X: 0,
                                                Y: 0
                                            }]), e.enabled = !e.enabled, i(e)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(rt, {
                                ar: o
                            }), n.json.Coordinates.map((function(e, t) {
                                return Object(Qe.jsx)(rt, {
                                    ar: [{
                                        blocks: [{
                                            title: (t + 1).toString(),
                                            type: _e.Empty
                                        }, {
                                            title: "X",
                                            type: _e.Number,
                                            nvalue: e.X,
                                            onChange: function(e) {
                                                return function(e, t) {
                                                    var a = Object(Ke.a)({}, n);
                                                    a.json.Coordinates || (a.json.Coordinates = []), a.json.Coordinates[e].X = t, i(a)
                                                }(t, e)
                                            }
                                        }, {
                                            title: "Y",
                                            type: _e.Number,
                                            nvalue: e.Y,
                                            onChange: function(e) {
                                                return function(e, t) {
                                                    var a = Object(Ke.a)({}, n);
                                                    a.json.Coordinates || (a.json.Coordinates = []), a.json.Coordinates[e].Y = t, i(a)
                                                }(t, e)
                                            }
                                        }, {
                                            title: "Del",
                                            type: _e.Button,
                                            disabled: n.json.Coordinates.length <= 1,
                                            className: "btn-outline-danger",
                                            onClick: function(e) {
                                                return function(e) {
                                                    if (window.confirm("Are you sure to delete this?")) {
                                                        var t = Object(Ke.a)({}, n);
                                                        t.json.Coordinates.splice(e, 1), i(t)
                                                    }
                                                }(t)
                                            }
                                        }]
                                    }]
                                })
                            }))]
                        }) : ""]
                    })
                },
                mt = function(e) {
                    var t = e.title,
                        n = e.imageSet,
                        i = e.onUpdate,
                        o = e.disableCount,
                        s = e.disableCollapse,
                        r = Object(a.useMemo)((function() {
                            return [{
                                blocks: [{
                                    title: "Image",
                                    type: _e.SelectFile,
                                    nvalue: n.json.ImageIndex,
                                    onChange: l
                                }, {
                                    title: "Count",
                                    type: _e.Number,
                                    nvalue: n.json.ImagesCount,
                                    onChange: c,
                                    disabled: o
                                }]
                            }, {
                                blocks: [{
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: Math.round((78.46 / 100) * n.json.X),
                                    onChange: d
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: Math.round((78.46 / 100) * n.json.Y),
                                    onChange: u
                                }]
                            }]
                        }), [n]);

                    function l(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.ImageIndex = e, i(t)
                    }

                    function d(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.X = e, i(t)
                    }

                    function c(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.ImagesCount = e, i(t)
                    }

                    function u(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.Y = e, i(t)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), s ? "" : Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, n);
                                            e.enabled = !e.enabled, i(e)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled || s ? Object(Qe.jsx)(ze.a.Body, {
                            children: Object(Qe.jsx)(rt, {
                                ar: r
                            })
                        }) : ""]
                    })
                },
                ht = function(e) {
                    var t = e.title,
                        n = e.scale,
                        i = e.onUpdate,
                        o = Object(a.useMemo)((function() {
                            var e, t, a, i, o, m;
                            return [{
                                blocks: [{
                                    title: "Pointer",
                                    type: _e.SelectFile,
                                    nvalue: null === (e = n.pointerScaleJson) || void 0 === e ? void 0 : e.PointerImageIndex,
                                    onChange: s
                                }]
                            }, {
                                blocks: [{
                                    title: "Center of rotation",
                                    type: _e.Empty
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (t = n.pointerScaleJson) || void 0 === t ? void 0 : t.CenterX) ? n.pointerScaleJson.CenterX : 0,
                                    onChange: r
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (a = n.pointerScaleJson) || void 0 === a ? void 0 : a.CenterY) ? n.pointerScaleJson.CenterY : 0,
                                    onChange: l
                                }]
                            }, {
                                blocks: [{
                                    title: "Start angle",
                                    type: _e.Number,
                                    nvalue: (null === (i = n.pointerScaleJson) || void 0 === i ? void 0 : i.RangeFrom) ? n.pointerScaleJson.RangeFrom : 0,
                                    onChange: c
                                }, {
                                    title: "End angle",
                                    type: _e.Number,
                                    nvalue: (null === (o = n.pointerScaleJson) || void 0 === o ? void 0 : o.RangeTo) ? n.pointerScaleJson.RangeTo : 360,
                                    onChange: u
                                }]
                            }, {
                                blocks: [{
                                    title: "Pointer offset",
                                    type: _e.Empty
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (m = n.pointerScaleJson) || void 0 === m ? void 0 : m.PointerCenterOfRotationY) ? n.pointerScaleJson.PointerCenterOfRotationY : 0,
                                    onChange: d
                                }]
                            }]
                        }), [n]);

                    function s(e) {
                        var t = Object(Ke.a)({}, n);
                        t.pointerScaleJson.PointerImageIndex = e, i(t)
                    }

                    function r(e) {
                        var t = Object(Ke.a)({}, n);
                        t.pointerScaleJson.CenterX = e, i(t)
                    }

                    function l(e) {
                        var t = Object(Ke.a)({}, n);
                        t.pointerScaleJson.CenterY = e, i(t)
                    }

                    function d(e) {
                        var t = Object(Ke.a)({}, n);
                        t.pointerScaleJson.PointerCenterOfRotationY = e, i(t)
                    }

                    function c(e) {
                        var t = Object(Ke.a)({}, n);
                        t.pointerScaleJson.RangeFrom = e, i(t)
                    }

                    function u(e) {
                        var t = Object(Ke.a)({}, n);
                        t.pointerScaleJson.RangeTo = e, i(t)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function(e) {
                                            var t = Object(Ke.a)({}, n);
                                            t.enabled = !t.enabled, t.enabled && !t.pointerScaleJson && (t.pointerScaleJson = new A), i(t)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(rt, {
                                ar: o
                            }), Object(Qe.jsx)(lt, {
                                title: "bottom image",
                                image: Object(Ke.a)({}, n.bottomImage),
                                onUpdate: function(e) {
                                    var t = Object(Ke.a)({}, n);
                                    t.bottomImage = e, i(t)
                                }
                            })]
                        }) : ""]
                    })
                },
                gt = function(e) {
                    var t = e.progress,
                        n = (e.title, e.onUpdate),
                        a = e.showImageProgress,
                        i = e.showIconProgress,
                        o = (e.showPointerProgress, e.showCircleScaleProgress);
                    return Object(Qe.jsxs)("div", {
                        children: [a ? Object(Qe.jsx)(mt, {
                            title: "Image progress",
                            onUpdate: function(e) {
                                var a = Object(Ke.a)({}, t);
                                a.imageProgress = e, n(a)
                            },
                            imageSet: t.imageProgress
                        }) : "", i ? Object(Qe.jsx)(ut, {
                            title: "Icon set progress",
                            onUpdate: function(e) {
                                var a = Object(Ke.a)({}, t);
                                a.iconSetProgress = e, n(a)
                            },
                            iconSet: t.iconSetProgress
                        }) : "", i ? Object(Qe.jsx)(ht, {
                            title: "Pointer progress",
                            onUpdate: function(e) {
                                var a = Object(Ke.a)({}, t);
                                a.scale = e, n(a)
                            },
                            scale: t.scale
                        }) : "", o ? Object(Qe.jsx)(ct, {
                            title: "Circle progress",
                            onUpdate: function(e) {
                                var a = Object(Ke.a)({}, t);
                                a.circleScale = e, n(a)
                            },
                            scale: t.circleScale
                        }) : ""]
                    })
                },
                bt = function(e) {
                    var t = e.title,
                        n = e.shortcut,
                        i = e.onUpdate,
                        o = Object(a.useMemo)((function() {
                            var e, t, a, i, o, c;
                            return [{
                                blocks: [{
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (e = n.json) || void 0 === e ? void 0 : e.TopLeftX) ? Math.round((78.46 / 100) * n.json.TopLeftX) : 0,
                                    onChange: s
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (t = n.json) || void 0 === t ? void 0 : t.TopLeftY) ? Math.round((78.46 / 100) * n.json.TopLeftY) : 0,
                                    onChange: r
                                }, {
                                    title: "Width",
                                    type: _e.Number,
                                    nvalue: (null === (a = n.json) || void 0 === a ? void 0 : a.BottomRightX) ? (null === (i = n.json) || void 0 === i ? void 0 : i.BottomRightX) - n.json.TopLeftX : 0,
                                    onChange: l
                                }, {
                                    title: "Height",
                                    type: _e.Number,
                                    nvalue: (null === (o = n.json) || void 0 === o ? void 0 : o.BottomRightY) ? (null === (c = n.json) || void 0 === c ? void 0 : c.BottomRightY) - n.json.TopLeftY : 0,
                                    onChange: d
                                }]
                            }]
                        }), [n]);

                    function s(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.TopLeftX = e, i(t)
                    }

                    function r(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.TopLeftY = e, i(t)
                    }

                    function l(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.BottomRightX = t.json.TopLeftX ? t.json.TopLeftX + e : e, i(t)
                    }

                    function d(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.BottomRightY = t.json.TopLeftY ? t.json.TopLeftY + e : e, i(t)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, n);
                                            e.enabled = !e.enabled, i(e)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsx)(ze.a.Body, {
                            children: Object(Qe.jsx)(rt, {
                                ar: o
                            })
                        }) : ""]
                    })
                },
                jt = function(e) {
                    var t = e.activity,
                        n = e.title,
                        i = e.onUpdateActivity,
                        o = e.type,
                        s = e.showImageProgress,
                        r = e.showIconProgress,
                        l = e.showPointerProgress,
                        d = e.showCircleScaleProgress,
                        c = Object(a.useMemo)((function() {
                            var e, n;
                            return [{
                                disabled: !(o === x.Steps || o === x.Calories),
                                blocks: [{
                                    title: "Prefix",
                                    type: _e.SelectFile,
                                    nvalue: t.aElement.prefix,
                                    onChange: u
                                }]
                            }, {
                                disabled: o === x.Distance,
                                blocks: [{
                                    title: "NoData",
                                    type: _e.SelectFile,
                                    nvalue: t.aElement.noData,
                                    onChange: m
                                }]
                            }, {
                                disabled: !(o === x.Steps || o === x.HeartRate),
                                blocks: [{
                                    title: "Suffix",
                                    type: _e.SelectFile,
                                    nvalue: t.aElement.suffix,
                                    onChange: h
                                }]
                            }, {
                                disabled: !(o === x.Distance),
                                blocks: [{
                                    title: "DecimalPointer",
                                    type: _e.SelectFile,
                                    nvalue: t.aElement.decimalPoint,
                                    onChange: g
                                }, {
                                    title: "Suffix",
                                    type: _e.SelectFile,
                                    nvalue: t.aElement.suffix,
                                    onChange: b
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (e = t.aElement.suffixImageCoordinates) || void 0 === e ? void 0 : e.X) ? t.aElement.suffixImageCoordinates.X : 0,
                                    onChange: j
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (n = t.aElement.suffixImageCoordinates) || void 0 === n ? void 0 : n.Y) ? t.aElement.suffixImageCoordinates.Y : 0,
                                    onChange: p
                                }]
                            }]
                        }), [t]);

                    function u(e) {
                        var n = Object(Ke.a)({}, t);
                        n.aElement.prefix = e, i(n)
                    }

                    function m(e) {
                        var n = Object(Ke.a)({}, t);
                        n.aElement.noData = e, i(n)
                    }

                    function h(e) {
                        var n = Object(Ke.a)({}, t);
                        n.aElement.suffix = e, i(n)
                    }

                    function g(e) {
                        var n = Object(Ke.a)({}, t);
                        n.aElement.decimalPoint = e, i(n)
                    }

                    function b(e) {
                        var n = Object(Ke.a)({}, t);
                        n.aElement.suffixKM = e, i(n)
                    }

                    function j(e) {
                        var n = Object(Ke.a)({}, t);
                        n.aElement.suffixImageCoordinates || (n.aElement.suffixImageCoordinates = new M), n.aElement.suffixImageCoordinates.X = e, i(n)
                    }

                    function p(e) {
                        var n = Object(Ke.a)({}, t);
                        n.aElement.suffixImageCoordinates || (n.aElement.suffixImageCoordinates = new M), n.aElement.suffixImageCoordinates.X = e, i(n)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.collapsed = !e.collapsed, i(e)
                            },
                            children: n
                        }), t.collapsed ? "" : Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(dt, {
                                title: "Number",
                                digit: t.aElement.imageNumber,
                                onUpdate: function(e) {
                                    var n = Object(Ke.a)({}, t);
                                    n.aElement.imageNumber = e, n.aElement.enabled = n.aElement.icon.enabled || n.aElement.imageNumber.enabled || n.aElement.shortcut.enabled, i(n)
                                },
                                followDisabled: !0,
                                showDelimiter: !1,
                                paddingDisabled: !0
                            }), Object(Qe.jsx)(rt, {
                                ar: c
                            }), Object(Qe.jsx)(lt, {
                                title: "Icon",
                                image: t.aElement.icon,
                                onUpdate: function(e) {
                                    var n = Object(Ke.a)({}, t);
                                    n.aElement.icon = e, n.aElement.enabled = n.aElement.icon.enabled || n.aElement.imageNumber.enabled || n.aElement.shortcut.enabled, i(n)
                                }
                            }), Object(Qe.jsx)(bt, {
                                title: "Shortcut",
                                shortcut: t.aElement.shortcut,
                                onUpdate: function(e) {
                                    var n = Object(Ke.a)({}, t);
                                    n.aElement.shortcut = e, n.aElement.enabled = n.aElement.icon.enabled || n.aElement.imageNumber.enabled || n.aElement.shortcut.enabled, i(n)
                                }
                            }), Object(Qe.jsx)(gt, {
                                progress: t.aProgress,
                                title: "Progress",
                                onUpdate: function(e) {
                                    var n = Object(Ke.a)({}, t);
                                    n.aProgress = e, i(n)
                                },
                                showImageProgress: s,
                                showIconProgress: r,
                                showPointerProgress: l,
                                showCircleScaleProgress: d
                            })]
                        })]
                    })
                },
                pt = function(e) {
                    var t = e.title,
                        n = e.ampm,
                        i = e.onUpdate,
                        o = Object(a.useMemo)((function() {
                            var e, t, a, i;
                            return [{
                                blocks: [{
                                    title: "AM",
                                    type: _e.SelectFile,
                                    nvalue: n.json.AmImageIndexEN,
                                    onChange: s
                                }, {
                                    title: "PM",
                                    type: _e.SelectFile,
                                    nvalue: n.json.PmImageIndexEN,
                                    onChange: r
                                }]
                            }, {
                                blocks: [{
                                    title: "Common",
                                    type: _e.Empty
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: n.json.CommonX ? Math.round((78.46 / 100) * n.json.CommonX) : 0,
                                    onChange: l
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: n.json.CommonY ? Math.round((78.46 / 100) * n.json.CommonY) : 0,
                                    onChange: d
                                }]
                            }, {
                                blocks: [{
                                    title: "AM",
                                    type: _e.Empty
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (e = n.json.CoordinatesAM) || void 0 === e ? void 0 : e.X) ? n.json.CoordinatesAM.X : 0,
                                    onChange: c
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (t = n.json.CoordinatesAM) || void 0 === t ? void 0 : t.Y) ? n.json.CoordinatesAM.Y : 0,
                                    onChange: u
                                }]
                            }, {
                                blocks: [{
                                    title: "PM",
                                    type: _e.Empty
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (a = n.json.CoordinatesPM) || void 0 === a ? void 0 : a.X) ? n.json.CoordinatesPM.X : 0,
                                    onChange: m
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (i = n.json.CoordinatesPM) || void 0 === i ? void 0 : i.Y) ? n.json.CoordinatesPM.Y : 0,
                                    onChange: h
                                }]
                            }]
                        }), [n]);

                    function s(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.AmImageIndexEN = e, i(t)
                    }

                    function r(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.PmImageIndexEN = e, i(t)
                    }

                    function l(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CommonX = e, i(t)
                    }

                    function d(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CommonY = e, i(t)
                    }

                    function c(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CoordinatesAM || (t.json.CoordinatesAM = new M), t.json.CoordinatesAM.X = e, i(t)
                    }

                    function u(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CoordinatesAM || (t.json.CoordinatesAM = new M), t.json.CoordinatesAM.Y = e, i(t)
                    }

                    function m(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CoordinatesPM || (t.json.CoordinatesPM = new M), t.json.CoordinatesPM.X = e, i(t)
                    }

                    function h(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CoordinatesPM || (t.json.CoordinatesPM = new M), t.json.CoordinatesPM.Y = e, i(t)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, n);
                                            e.enabled = !e.enabled, i(e)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsx)(ze.a.Body, {
                            children: Object(Qe.jsx)(rt, {
                                ar: o
                            })
                        }) : ""]
                    })
                },
                vt = function() {
                    var e, t, n, i, o, s, r, l = Object(a.useContext)(m),
                        d = l.watchface,
                        c = l.setWatchface;

                    function u(e) {
                        var t = Object(Ke.a)({}, d);
                        t.aod.date = e, c(t)
                    }
                    return Object(Qe.jsx)(Qe.Fragment, {
                        children: Object(Qe.jsxs)(ze.a, {
                            children: [Object(Qe.jsx)(ze.a.Header, {
                                onClick: function() {
                                    var e = Object(Ke.a)({}, d);
                                    e.aod || (e.aod = new Me), e.aod.date || (e.aod.date = new Se), e.aod.date.collapsed = !d.aod.date.collapsed, c(e)
                                },
                                children: "Date"
                            }), Object(Qe.jsxs)(ze.a.Body, {
                                className: "".concat((null === (e = d.aod) || void 0 === e || null === (t = e.date) || void 0 === t ? void 0 : t.collapsed) ? "collapse" : ""),
                                children: [Object(Qe.jsx)(dt, {
                                    title: "Month",
                                    digit: Object(Ke.a)({}, null === (n = d.aod) || void 0 === n || null === (i = n.date) || void 0 === i ? void 0 : i.month),
                                    onUpdate: function(e) {
                                        var t = Object(Ke.a)({}, d.aod.date);
                                        t.month = e, u(t)
                                    },
                                    followDisabled: !0,
                                    showDelimiter: !0,
                                    showDataType: !0
                                }), Object(Qe.jsx)(dt, {
                                    title: "Day",
                                    digit: Object(Ke.a)({}, null === (o = d.aod) || void 0 === o || null === (s = o.date) || void 0 === s ? void 0 : s.day),
                                    onUpdate: function(e) {
                                        var t = Object(Ke.a)({}, d.aod.date);
                                        t.day = e, u(t)
                                    },
                                    showDelimiter: !0,
                                    showDataType: !0
                                }), Object(Qe.jsx)(mt, {
                                    title: "Weekday",
                                    imageSet: Object(Ke.a)({}, null === (r = d.aod) || void 0 === r ? void 0 : r.weekday),
                                    onUpdate: function(e) {
                                        var t = Object(Ke.a)({}, d);
                                        t.aod.weekday = e, c(t)
                                    }
                                }), Object(Qe.jsx)(pt, {
                                    title: "Am / PM",
                                    ampm: Object(Ke.a)({}, d.aod.time.amPm),
                                    onUpdate: function(e) {
                                        var t = Object(Ke.a)({}, d);
                                        t.aod.time.amPm = e, c(t)
                                    }
                                })]
                            })]
                        })
                    })
                },
                ft = function() {
                    var e, t, n, i, o = Object(a.useContext)(m),
                        s = o.watchface,
                        r = o.setWatchface;
                    return Object(Qe.jsx)(Qe.Fragment, {
                        children: Object(Qe.jsxs)(ze.a, {
                            children: [Object(Qe.jsx)(ze.a.Header, {
                                onClick: function() {
                                    var e = Object(Ke.a)({}, s);
                                    e.aod || (e.aod = new Me), e.aod.dateOneLine || (e.aod.dateOneLine = new Ce), e.aod.dateOneLine.collapsed = !s.aod.dateOneLine.collapsed, r(e)
                                },
                                children: "Date OneLine"
                            }), Object(Qe.jsxs)(ze.a.Body, {
                                className: "".concat((null === (e = s.aod) || void 0 === e || null === (t = e.dateOneLine) || void 0 === t ? void 0 : t.collapsed) ? "collapse" : ""),
                                children: [Object(Qe.jsx)(rt, {
                                    ar: [{
                                        blocks: [{
                                            title: "Separator",
                                            type: _e.SelectFile,
                                            nvalue: null === (n = s.aod) || void 0 === n || null === (i = n.dateOneLine) || void 0 === i ? void 0 : i.separatorImageIndex,
                                            onChange: function(e) {
                                                var t = Object(Ke.a)({}, s);
                                                t.aod.dateOneLine.separatorImageIndex = e, r(t)
                                            }
                                        }]
                                    }]
                                }), Object(Qe.jsx)(dt, {
                                    title: "MonthAndDay",
                                    digit: Object(Ke.a)({}, s.aod.dateOneLine.monthAndDay),
                                    onUpdate: function(e) {
                                        var t = Object(Ke.a)({}, s);
                                        t.aod.dateOneLine.monthAndDay = e, r(t)
                                    },
                                    followDisabled: !0,
                                    showDelimiter: !1,
                                    showDataType: !1
                                })]
                            })]
                        })
                    })
                },
                xt = function(e) {
                    var t = e.title,
                        n = e.clockHand,
                        i = e.onUpdate,
                        o = (e.showAngle, e.onCopyFromNormal),
                        s = e.disableCenter,
                        r = Object(a.useMemo)((function() {
                            var e, t, a, i, o, r, b, j, p, v, f, x, O, y, I, w, C, S;
                            return [{
                                blocks: [{
                                    title: "Pointer",
                                    type: _e.SelectFile,
                                    nvalue: null === (e = n.json) || void 0 === e ? void 0 : e.ImageIndex,
                                    onChange: l
                                }]
                            }, {
                                disabled: s,
                                blocks: [{
                                    title: "Center of rotation",
                                    type: _e.Empty
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (t = n.json) || void 0 === t || null === (a = t.CenterCoordinates) || void 0 === a ? void 0 : a.X) ? null === (i = n.json.CenterCoordinates) || void 0 === i ? void 0 : i.X : 0,
                                    onChange: d
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (o = n.json) || void 0 === o || null === (r = o.CenterCoordinates) || void 0 === r ? void 0 : r.Y) ? null === (b = n.json.CenterCoordinates) || void 0 === b ? void 0 : b.Y : 0,
                                    onChange: c
                                }]
                            }, {
                                blocks: [{
                                    title: "Pointer offset",
                                    type: _e.Empty
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (j = n.json) || void 0 === j ? void 0 : j.PointerCenterOfRotationY) ? n.json.PointerCenterOfRotationY : 0,
                                    onChange: u
                                }]
                            }, {
                                blocks: [{
                                    title: "Cover",
                                    type: _e.SelectFile,
                                    nvalue: null === (p = n.json) || void 0 === p || null === (v = p.CoverImage) || void 0 === v ? void 0 : v.ImageIndex,
                                    onChange: m
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (f = n.json) || void 0 === f || null === (x = f.CoverImage) || void 0 === x ? void 0 : x.X) ? null === (O = n.json) || void 0 === O || null === (y = O.CoverImage) || void 0 === y ? void 0 : y.X : 0,
                                    onChange: h
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (I = n.json) || void 0 === I || null === (w = I.CoverImage) || void 0 === w ? void 0 : w.Y) ? null === (C = n.json) || void 0 === C || null === (S = C.CoverImage) || void 0 === S ? void 0 : S.Y : 0,
                                    onChange: g
                                }]
                            }]
                        }), [n]);

                    function l(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.ImageIndex = e, i(t)
                    }

                    function d(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CenterCoordinates.X = e, i(t)
                    }

                    function c(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CenterCoordinates.Y = e, i(t)
                    }

                    function u(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.PointerCenterOfRotationY = e, i(t)
                    }

                    function m(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CoverImage || (t.json.CoverImage = new O), t.json.CoverImage.ImageIndex = e, i(t)
                    }

                    function h(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CoverImage || (t.json.CoverImage = new O), t.json.CoverImage.X = e, i(t)
                    }

                    function g(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.CoverImage || (t.json.CoverImage = new O), t.json.CoverImage.Y = e, i(t)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function(e) {
                                            var t = Object(Ke.a)({}, n);
                                            t.enabled = !t.enabled, t.enabled && !t.json && (t.json = new Y), i(t)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsxs)(ze.a.Body, {
                            children: [o ? Object(Qe.jsx)("div", {
                                style: {
                                    clear: "both"
                                },
                                children: Object(Qe.jsx)("button", {
                                    className: "btn btn-sm btn-secondary mb-1",
                                    style: {
                                        float: "right"
                                    },
                                    onClick: o,
                                    children: "Copy from normal screen"
                                })
                            }) : "", Object(Qe.jsx)(rt, {
                                ar: r
                            })]
                        }) : ""]
                    })
                },
                Ot = function() {
                    var e, t, n, i, o, s, r = Object(a.useContext)(m),
                        l = r.watchface,
                        d = r.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            onClick: function() {
                                var e = Object(Ke.a)({}, l);
                                e.aod.time.timeAnalog.collapsed = !l.aod.time.timeAnalog.collapsed, d(e)
                            },
                            children: "Time Analog"
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            className: "".concat(l.aod.time.timeAnalog.collapsed ? "collapse" : ""),
                            children: [Object(Qe.jsx)(xt, {
                                title: "Hours",
                                clockHand: Object(Ke.a)({}, l.aod.time.timeAnalog.hours),
                                showAngle: !1,
                                onUpdate: function(e) {
                                    var t = Object(Ke.a)({}, l);
                                    t.aod.time.timeAnalog.hours = e, d(t)
                                },
                                disableCenter: !0
                            }), Object(Qe.jsx)(xt, {
                                title: "Minutes",
                                clockHand: Object(Ke.a)({}, l.aod.time.timeAnalog.minutes),
                                onUpdate: function(e) {
                                    var t = Object(Ke.a)({}, l);
                                    t.aod.time.timeAnalog.minutes = e, d(t)
                                },
                                showAngle: !1,
                                disableCenter: !0
                            }), Object(Qe.jsx)(rt, {
                                ar: [{
                                    blocks: [{
                                        title: "X",
                                        type: _e.Number,
                                        nvalue: (null === (e = l.aod.time.timeAnalog) || void 0 === e || null === (t = e.commonCenterCoordinates) || void 0 === t ? void 0 : t.X) ? null === (n = l.aod.time.timeAnalog) || void 0 === n ? void 0 : n.commonCenterCoordinates.X : 0,
                                        onChange: function(e) {
                                            var t = Object(Ke.a)({}, l);
                                            t.aod.time.timeAnalog.commonCenterCoordinates || (t.aod.time.timeAnalog.commonCenterCoordinates = new M), t.aod.time.timeAnalog.commonCenterCoordinates.X = e, d(t)
                                        }
                                    }, {
                                        title: "Y",
                                        type: _e.Number,
                                        nvalue: (null === (i = l.aod.time.timeAnalog) || void 0 === i || null === (o = i.commonCenterCoordinates) || void 0 === o ? void 0 : o.Y) ? null === (s = l.aod.time.timeAnalog) || void 0 === s ? void 0 : s.commonCenterCoordinates.Y : 0,
                                        onChange: function(e) {
                                            var t = Object(Ke.a)({}, l);
                                            t.aod.time.timeAnalog.commonCenterCoordinates || (t.aod.time.timeAnalog.commonCenterCoordinates = new M), t.aod.time.timeAnalog.commonCenterCoordinates.Y = e, d(t)
                                        }
                                    }]
                                }]
                            })]
                        })]
                    })
                },
                yt = function(e) {
                    var t = e.title,
                        n = e.digit,
                        a = e.amountOfDigits,
                        i = e.onUpdate;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, n);
                                            e.enabled = !e.enabled, i(e)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsxs)(ze.a.Body, {
                            children: [a > 4 ? Object(Qe.jsx)(mt, {
                                title: "Ten Thousands",
                                imageSet: new re(10, n.json.TenThousands),
                                onUpdate: function(e) {
                                    var t = Object(Ke.a)({}, n);
                                    t.json.TenThousands = e.json, i(t)
                                },
                                disableCount: !0,
                                disableCollapse: !0
                            }) : "", a > 3 ? Object(Qe.jsx)(mt, {
                                title: "Thousands",
                                imageSet: new re(10, n.json.Thousands),
                                onUpdate: function(e) {
                                    var t = Object(Ke.a)({}, n);
                                    t.json.Thousands = e.json, i(t)
                                },
                                disableCount: !0,
                                disableCollapse: !0
                            }) : "", a > 2 ? Object(Qe.jsx)(mt, {
                                title: "Hundreds",
                                imageSet: new re(10, n.json.Hundreds),
                                onUpdate: function(e) {
                                    var t = Object(Ke.a)({}, n);
                                    t.json.Hundreds = e.json, i(t)
                                },
                                disableCount: !0,
                                disableCollapse: !0
                            }) : "", a > 1 ? Object(Qe.jsx)(mt, {
                                title: "Tens",
                                imageSet: new re(10, n.json.Tens),
                                onUpdate: function(e) {
                                    var t = Object(Ke.a)({}, n);
                                    t.json.Tens = e.json, i(t)
                                },
                                disableCount: !0,
                                disableCollapse: !0
                            }) : "", a > 0 ? Object(Qe.jsx)(mt, {
                                title: "Ones",
                                imageSet: new re(10, n.json.Ones),
                                onUpdate: function(e) {
                                    var t = Object(Ke.a)({}, n);
                                    t.json.Ones = e.json, i(t)
                                },
                                disableCount: !0,
                                disableCollapse: !0
                            }) : ""]
                        }) : ""]
                    })
                },
                It = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.aod.time.timeSeparateDigits.collapsed = !t.aod.time.timeSeparateDigits.collapsed, n(e)
                            },
                            children: "Time Separate Digits"
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            className: "".concat(t.aod.time.timeSeparateDigits.collapsed ? "collapse" : ""),
                            children: [Object(Qe.jsx)(rt, {
                                ar: [{
                                    blocks: [{
                                        title: "Padding Zero Hours",
                                        type: _e.Checkbox,
                                        checked: t.aod.time.timeSeparateDigits.paddingZero,
                                        onChange: function(e) {
                                            var a = Object(Ke.a)({}, t);
                                            a.aod.time.timeSeparateDigits.paddingZero = e, n(a)
                                        }
                                    }]
                                }]
                            }), Object(Qe.jsx)(yt, {
                                title: "Hours Digits",
                                digit: Object(Ke.a)({}, t.aod.time.timeSeparateDigits.hours),
                                amountOfDigits: 2,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.aod.time.timeSeparateDigits.hours = e, n(a)
                                }
                            }), Object(Qe.jsx)(yt, {
                                title: "Minutes Digits",
                                digit: Object(Ke.a)({}, t.aod.time.timeSeparateDigits.minutes),
                                amountOfDigits: 2,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.aod.time.timeSeparateDigits.minutes = e, n(a)
                                }
                            }), Object(Qe.jsx)(lt, {
                                title: "Separator",
                                image: Object(Ke.a)({}, t.aod.time.timeSeparateDigits.separator),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.aod.time.timeSeparateDigits.separator = e, n(a)
                                }
                            })]
                        })]
                    })
                },
                wt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(Qe.Fragment, {
                        children: [Object(Qe.jsx)(It, {}), Object(Qe.jsx)(Ot, {}), Object(Qe.jsx)(vt, {}), Object(Qe.jsx)(ft, {}), Object(Qe.jsx)(jt, {
                            activity: Object(Ke.a)({}, t.aod.steps),
                            title: "Steps",
                            type: x.Steps,
                            onUpdateActivity: function(e) {
                                var a = Object(Ke.a)({}, t);
                                a.aod.steps = e, n(a)
                            },
                            showImageProgress: !0,
                            showIconProgress: !0,
                            showPointerProgress: !0,
                            showCircleScaleProgress: !0
                        })]
                    })
                },
                Ct = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            title: "Click to open / close",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.activity.collapsed = !e.activity.collapsed, n(e)
                            },
                            children: "Activity"
                        }), t.activity.collapsed ? "" : Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(jt, {
                                title: "Steps",
                                activity: Object(Ke.a)({}, t.activity.steps),
                                onUpdateActivity: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.steps = e, n(a)
                                },
                                type: x.Steps,
                                showImageProgress: !0,
                                showIconProgress: !0,
                                showPointerProgress: !0,
                                showCircleScaleProgress: !0
                            }), Object(Qe.jsx)(jt, {
                                title: "Calories",
                                activity: Object(Ke.a)({}, t.activity.calories),
                                onUpdateActivity: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.calories = e, n(a)
                                },
                                type: x.Calories,
                                showImageProgress: !0,
                                showIconProgress: !0,
                                showPointerProgress: !0,
                                showCircleScaleProgress: !0
                            }), Object(Qe.jsx)(jt, {
                                title: "Hearth rate",
                                activity: Object(Ke.a)({}, t.activity.heartRate),
                                onUpdateActivity: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.heartRate = e, n(a)
                                },
                                type: x.HeartRate,
                                showImageProgress: !0,
                                showIconProgress: !0,
                                showPointerProgress: !0,
                                showCircleScaleProgress: !0
                            }), Object(Qe.jsx)(jt, {
                                title: "Distance",
                                activity: Object(Ke.a)({}, t.activity.distance),
                                onUpdateActivity: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.distance = e, n(a)
                                },
                                type: x.Distance,
                                showImageProgress: !1,
                                showIconProgress: !1,
                                showPointerProgress: !1,
                                showCircleScaleProgress: !1
                            }), Object(Qe.jsx)(jt, {
                                title: "PAI",
                                activity: Object(Ke.a)({}, t.activity.pai),
                                onUpdateActivity: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.pai = e, n(a)
                                },
                                type: x.Pai,
                                showImageProgress: !0,
                                showIconProgress: !1,
                                showPointerProgress: !1,
                                showCircleScaleProgress: !1
                            }), Object(Qe.jsx)(jt, {
                                title: "Stand up",
                                activity: Object(Ke.a)({}, t.activity.standUp),
                                onUpdateActivity: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.standUp = e, n(a)
                                },
                                type: x.StandUp,
                                showImageProgress: !0,
                                showIconProgress: !0,
                                showPointerProgress: !0,
                                showCircleScaleProgress: !0
                            })]
                        })]
                    })
                },
                St = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface,
                        i = Object(a.useMemo)((function() {
                            return [{
                                blocks: [{
                                    title: "Color",
                                    type: _e.Color,
                                    svalue: t.background.color,
                                    onChange: o
                                }]
                            }]
                        }), [t.background]);

                    function o(e) {
                        n(Object(Ke.a)(Object(Ke.a)({}, t), {}, {
                            background: Object(Ke.a)(Object(Ke.a)({}, t.background), {}, {
                                color: e
                            })
                        }))
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            className: "clickable",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.background.collapsed = !e.background.collapsed, n(e)
                            },
                            children: "Background"
                        }), t.background.collapsed ? "" : Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(rt, {
                                ar: i
                            }), Object(Qe.jsx)(lt, {
                                title: "Preview",
                                image: Object(Ke.a)({}, t.background.preview),
                                onUpdate: function(e) {
                                    n(Object(Ke.a)(Object(Ke.a)({}, t), {}, {
                                        background: Object(Ke.a)(Object(Ke.a)({}, t.background), {}, {
                                            preview: e
                                        })
                                    }))
                                }
                            }), Object(Qe.jsx)(lt, {
                                title: "Background",
                                image: Object(Ke.a)({}, t.background.image),
                                onUpdate: function(e) {
                                    n(Object(Ke.a)(Object(Ke.a)({}, t), {}, {
                                        background: Object(Ke.a)(Object(Ke.a)({}, t.background), {}, {
                                            image: e
                                        })
                                    }))
                                }
                            }), Object(Qe.jsx)(lt, {
                                title: "Floating layer",
                                image: Object(Ke.a)({}, t.background.floatingLayer),
                                onUpdate: function(e) {
                                    n(Object(Ke.a)(Object(Ke.a)({}, t), {}, {
                                        background: Object(Ke.a)(Object(Ke.a)({}, t.background), {}, {
                                            floatingLayer: e
                                        })
                                    }))
                                }
                            })]
                        })]
                    })
                },
                Dt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsx)(Qe.Fragment, {
                        children: Object(Qe.jsxs)(ze.a, {
                            children: [Object(Qe.jsx)(ze.a.Header, {
                                onClick: function() {
                                    var e = Object(Ke.a)({}, t);
                                    e.date.collapsed = !t.date.collapsed, n(e)
                                },
                                children: "Date"
                            }), Object(Qe.jsxs)(ze.a.Body, {
                                className: "".concat(t.date.collapsed ? "collapse" : ""),
                                children: [Object(Qe.jsx)(rt, {
                                    ar: [{
                                        blocks: [{
                                            title: "One Line Year",
                                            type: _e.Checkbox,
                                            checked: t.date.oneLineYear,
                                            onChange: function(e) {
                                                var a = Object(Ke.a)({}, t);
                                                a.date.oneLineYear = e, n(a)
                                            }
                                        }, {
                                            title: "One Line Month",
                                            type: _e.Checkbox,
                                            checked: t.date.oneLineMonth,
                                            onChange: function(e) {
                                                var a = Object(Ke.a)({}, t);
                                                a.date.oneLineMonth = e, n(a)
                                            }
                                        }, {
                                            title: "Delimiter",
                                            type: _e.SelectFile,
                                            nvalue: t.date.oneLineDelimiter,
                                            onChange: function(e) {
                                                var a = Object(Ke.a)({}, t);
                                                a.date.oneLineDelimiter = e, n(a)
                                            }
                                        }]
                                    }]
                                }), t.date.oneLineMonth ? "" : Object(Qe.jsx)(dt, {
                                    title: "Year",
                                    digit: Object(Ke.a)({}, t.date.year),
                                    onUpdate: function(e) {
                                        var a = Object(Ke.a)({}, t);
                                        a.date.year = e, n(a)
                                    },
                                    followDisabled: !0,
                                    showDelimiter: !t.date.oneLineYear,
                                    showDataType: !t.date.oneLineYear
                                }), t.date.oneLineYear ? "" : Object(Qe.jsxs)(Qe.Fragment, {
                                    children: [Object(Qe.jsx)(dt, {
                                        title: "Month",
                                        digit: Object(Ke.a)({}, t.date.month),
                                        onUpdate: function(e) {
                                            var a = Object(Ke.a)({}, t);
                                            a.date.month = e, n(a)
                                        },
                                        showDelimiter: !t.date.oneLineMonth,
                                        showDataType: !t.date.oneLineMonth
                                    }), t.date.oneLineMonth ? "" : Object(Qe.jsx)(dt, {
                                        title: "Day",
                                        digit: Object(Ke.a)({}, t.date.day),
                                        onUpdate: function(e) {
                                            var a = Object(Ke.a)({}, t);
                                            a.date.day = e, n(a)
                                        },
                                        showDelimiter: !0,
                                        showDataType: !0
                                    })]
                                }), Object(Qe.jsx)(mt, {
                                    title: "Month as word",
                                    imageSet: Object(Ke.a)({}, t.date.monthAsWord),
                                    onUpdate: function(e) {
                                        var a = Object(Ke.a)({}, t);
                                        a.date.monthAsWord = e, n(a)
                                    }
                                }), Object(Qe.jsx)(mt, {
                                    title: "Weekday",
                                    imageSet: Object(Ke.a)({}, t.date.weekday),
                                    onUpdate: function(e) {
                                        var a = Object(Ke.a)({}, t);
                                        a.date.weekday = e, n(a)
                                    }
                                }), Object(Qe.jsx)(pt, {
                                    title: "AmPm",
                                    ampm: Object(Ke.a)({}, t.date.ampm),
                                    onUpdate: function(e) {
                                        var a = Object(Ke.a)({}, t);
                                        a.date.ampm = e, n(a)
                                    }
                                })]
                            })]
                        })
                    })
                },
                Nt = function(e) {
                    var t = e.title,
                        n = e.sw,
                        i = e.onUpdate,
                        o = Object(a.useMemo)((function() {
                            return [{
                                blocks: [{
                                    title: "Image ON",
                                    type: _e.SelectFile,
                                    nvalue: n.json.ImageIndexOn,
                                    onChange: s
                                }, {
                                    title: "Image OFF",
                                    type: _e.SelectFile,
                                    nvalue: n.json.ImageIndexOff,
                                    onChange: r
                                }, {
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: Math.round((78.46 / 100) * n.json.Coordinates.X),
                                    onChange: l
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: Math.round((78.46 / 100) * n.json.Coordinates.Y),
                                    onChange: d
                                }]
                            }]
                        }), [n]);

                    function s(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.ImageIndexOn = e, i(t)
                    }

                    function r(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.ImageIndexOff = e, i(t)
                    }

                    function l(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.Coordinates.X = e, i(t)
                    }

                    function d(e) {
                        var t = Object(Ke.a)({}, n);
                        t.json.Coordinates.Y = e, i(t)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, n);
                                            e.enabled = !e.enabled, i(e)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsx)(ze.a.Body, {
                            children: Object(Qe.jsx)(rt, {
                                ar: o
                            })
                        }) : ""]
                    })
                },
                Mt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;

                    function i(e) {
                        n(Object(Ke.a)(Object(Ke.a)({}, t), {}, {
                            status: e
                        }))
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.status.collapsed = !e.status.collapsed, n(e)
                            },
                            children: "Status"
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            className: "".concat(t.status.collapsed ? "collapse" : ""),
                            children: [Object(Qe.jsx)(Nt, {
                                title: "Bluetooth",
                                sw: Object(Ke.a)({}, t.status.bluetooth),
                                onUpdate: function(e) {
                                    i(Object(Ke.a)(Object(Ke.a)({}, t.status), {}, {
                                        bluetooth: e
                                    }))
                                }
                            }), Object(Qe.jsx)(Nt, {
                                title: "Do Not Disturb",
                                sw: Object(Ke.a)({}, t.status.doNotDisturb),
                                onUpdate: function(e) {
                                    i(Object(Ke.a)(Object(Ke.a)({}, t.status), {}, {
                                        doNotDisturb: e
                                    }))
                                }
                            }), Object(Qe.jsx)(Nt, {
                                title: "Alarm",
                                sw: Object(Ke.a)({}, t.status.alarm),
                                onUpdate: function(e) {
                                    i(Object(Ke.a)(Object(Ke.a)({}, t.status), {}, {
                                        alarm: e
                                    }))
                                }
                            }), Object(Qe.jsx)(Nt, {
                                title: "Lock",
                                sw: Object(Ke.a)({}, t.status.lock),
                                onUpdate: function(e) {
                                    i(Object(Ke.a)(Object(Ke.a)({}, t.status), {}, {
                                        lock: e
                                    }))
                                }
                            })]
                        })]
                    })
                },
                Pt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.time.timeAnalog.collapsed = !t.time.timeAnalog.collapsed, n(e)
                            },
                            children: "Time Analog"
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            className: "".concat(t.time.timeAnalog.collapsed ? "collapse" : ""),
                            children: [Object(Qe.jsx)(xt, {
                                title: "Hours",
                                clockHand: Object(Ke.a)({}, t.time.timeAnalog.hours),
                                showAngle: !1,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeAnalog.hours = e, n(a)
                                },
                                disableCenter: !1
                            }), Object(Qe.jsx)(xt, {
                                title: "Minutes",
                                clockHand: Object(Ke.a)({}, t.time.timeAnalog.minutes),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeAnalog.minutes = e, n(a)
                                },
                                showAngle: !1,
                                disableCenter: !1
                            }), Object(Qe.jsx)(xt, {
                                title: "Seconds",
                                clockHand: Object(Ke.a)({}, t.time.timeAnalog.seconds),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeAnalog.seconds = e, n(a)
                                },
                                showAngle: !1,
                                disableCenter: !1
                            })]
                        })]
                    })
                },
                Tt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.time.timeDigitalCommon.collapsed = !t.time.timeDigitalCommon.collapsed, n(e)
                            },
                            children: "Time Digital"
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            className: "".concat(t.time.timeDigitalCommon.collapsed ? "collapse" : ""),
                            children: [Object(Qe.jsx)(dt, {
                                title: "Hours",
                                digit: Object(Ke.a)({}, t.time.timeDigitalCommon.hours),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeDigitalCommon.hours = e, n(a)
                                },
                                followDisabled: !0,
                                showDelimiter: !0,
                                showDataType: !0
                            }), Object(Qe.jsx)(dt, {
                                title: "Minutes",
                                digit: Object(Ke.a)({}, t.time.timeDigitalCommon.minutes),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeDigitalCommon.minutes = e, n(a)
                                },
                                showDelimiter: !0,
                                showDataType: !0
                            }), Object(Qe.jsx)(dt, {
                                title: "Second",
                                digit: Object(Ke.a)({}, t.time.timeDigitalCommon.seconds),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeDigitalCommon.seconds = e, n(a)
                                },
                                showDelimiter: !0,
                                showDataType: !0
                            })]
                        })]
                    })
                },
                kt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.activity.collapsedSeparated = !t.activity.collapsedSeparated, n(e)
                            },
                            children: "Activity (Separate Digits)"
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            className: "".concat(t.activity.collapsedSeparated ? "collapse" : ""),
                            children: [Object(Qe.jsx)(yt, {
                                title: "Steps",
                                digit: Object(Ke.a)({}, t.activity.stepsSeparatedDigits),
                                amountOfDigits: 5,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.stepsSeparatedDigits = e, n(a)
                                }
                            }), Object(Qe.jsx)(yt, {
                                title: "Calories",
                                digit: Object(Ke.a)({}, t.activity.caloriesSeparatedDigits),
                                amountOfDigits: 4,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.caloriesSeparatedDigits = e, n(a)
                                }
                            }), Object(Qe.jsx)(yt, {
                                title: "Heart rate",
                                digit: Object(Ke.a)({}, t.activity.heartRateSeparatedDigits),
                                amountOfDigits: 3,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.heartRateSeparatedDigits = e, n(a)
                                }
                            }), Object(Qe.jsx)(yt, {
                                title: "Battery",
                                digit: Object(Ke.a)({}, t.activity.batterySeparatedDigits),
                                amountOfDigits: 3,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.activity.batterySeparatedDigits = e, n(a)
                                }
                            })]
                        })]
                    })
                },
                At = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.time.alarm.collapsed = !t.time.alarm.collapsed, n(e)
                            },
                            children: "Alarm"
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            className: "".concat(t.time.alarm.collapsed ? "collapse" : ""),
                            children: [Object(Qe.jsx)(dt, {
                                title: "Hours",
                                digit: Object(Ke.a)({}, t.time.alarm.alarmTime.hours),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.alarm.alarmTime.hours = e, n(a)
                                },
                                followDisabled: !0,
                                showDelimiter: !0,
                                showDataType: !0
                            }), Object(Qe.jsx)(dt, {
                                title: "Minutes",
                                digit: Object(Ke.a)({}, t.time.alarm.alarmTime.minutes),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.alarm.alarmTime.minutes = e, n(a)
                                },
                                showDelimiter: !0,
                                showDataType: !0
                            }), Object(Qe.jsx)(lt, {
                                title: "Alarm ON",
                                image: Object(Ke.a)({}, t.time.alarm.alarmImage),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.alarm.alarmImage = e, n(a)
                                }
                            }), Object(Qe.jsx)(lt, {
                                title: "Alarm OFF",
                                image: Object(Ke.a)({}, t.time.alarm.noAlarm),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.alarm.noAlarm = e, n(a)
                                }
                            }), Object(Qe.jsx)(bt, {
                                title: "Sunrise shortcut",
                                shortcut: Object(Ke.a)({}, t.time.alarm.shortcut),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.alarm.shortcut = e, n(a)
                                }
                            })]
                        })]
                    })
                },
                Lt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsxs)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.animation.collapsed = !e.animation.collapsed, n(e)
                            },
                            children: ["Animation", Object(Qe.jsx)("button", {
                                className: "btn btn-outline-success",
                                type: "button",
                                onClick: function() {
                                    var e = Object(Ke.a)({}, t),
                                        a = new H;
                                    a.FrameInterval = 0, a.ImageProgress = new y, a.Repeat = !0, a.PlayTimes = 1, e.animation.imageSetAnimation.push(a), n(e)
                                },
                                children: "Add"
                            })]
                        }), t.animation.collapsed ? "" : Object(Qe.jsx)(ze.a.Body, {
                            children: t.animation.imageSetAnimation.length >= 0 ? t.animation.imageSetAnimation.map((function(e, a) {
                                return Object(Qe.jsxs)(ze.a, {
                                    children: [Object(Qe.jsxs)(ze.a.Header, {
                                        className: "d-flex justify-content-between align-items-center",
                                        children: ["Animation ", a + 1, Object(Qe.jsx)("button", {
                                            className: "btn btn-outline-danger btn-sm",
                                            type: "button",
                                            onClick: function() {
                                                return function(e) {
                                                    if (window.confirm("Would you delete animation " + (e + 1))) {
                                                        var a = Object(Ke.a)({}, t);
                                                        a.animation.imageSetAnimation.splice(e, 1), n(a)
                                                    }
                                                }(a)
                                            },
                                            children: "Delete"
                                        })]
                                    }), Object(Qe.jsx)(rt, {
                                        ar: [{
                                            blocks: [{
                                                title: "frame interval (msec)",
                                                type: _e.Number,
                                                nvalue: e.FrameInterval,
                                                min: 1,
                                                onChange: function(e) {
                                                    return function(e, a) {
                                                        var i = Object(Ke.a)({}, t);
                                                        i.animation.imageSetAnimation[e].FrameInterval = a, n(i)
                                                    }(a, e)
                                                }
                                            }, {
                                                title: "play times",
                                                type: _e.Number,
                                                nvalue: e.PlayTimes,
                                                min: 1,
                                                max: 255,
                                                onChange: function(e) {
                                                    return function(e, a) {
                                                        var i = Object(Ke.a)({}, t);
                                                        i.animation.imageSetAnimation[e].PlayTimes = a, n(i)
                                                    }(a, e)
                                                }
                                            }, {
                                                title: "repeat",
                                                type: _e.Checkbox,
                                                checked: e.Repeat,
                                                onChange: function(e) {
                                                    return function(e, a) {
                                                        var i = Object(Ke.a)({}, t);
                                                        i.animation.imageSetAnimation[e].Repeat = a, n(i)
                                                    }(a, e)
                                                }
                                            }]
                                        }]
                                    }), Object(Qe.jsx)(mt, {
                                        title: "Image progress",
                                        imageSet: new re(null, e.ImageProgress),
                                        onUpdate: function(e) {
                                            return function(e, a) {
                                                var i = Object(Ke.a)({}, t);
                                                i.animation.imageSetAnimation[e].ImageProgress = a.json, n(i)
                                            }(a, e)
                                        }
                                    })]
                                })
                            })) : "no animation added"
                        })]
                    })
                },
                Et = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface,
                        i = Object(a.useMemo)((function() {
                            return [{
                                blocks: [{
                                    title: "Prefix",
                                    type: _e.SelectFile,
                                    nvalue: t.battery.text.prefix,
                                    onChange: o
                                }, {
                                    title: "NoData",
                                    type: _e.SelectFile,
                                    nvalue: t.battery.text.noData,
                                    onChange: s
                                }, {
                                    title: "Suffix",
                                    type: _e.SelectFile,
                                    nvalue: t.battery.text.suffix,
                                    onChange: r
                                }]
                            }]
                        }), [t.battery.text]);

                    function o(e) {
                        var a = Object(Ke.a)({}, t);
                        a.battery.text.prefix = e, n(a)
                    }

                    function s(e) {
                        var a = Object(Ke.a)({}, t);
                        a.battery.text.noData = e, n(a)
                    }

                    function r(e) {
                        var a = Object(Ke.a)({}, t);
                        a.battery.text.suffix = e, n(a)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.battery.collapsed = !e.battery.collapsed, n(e)
                            },
                            children: "Battery"
                        }), t.battery.collapsed ? "" : Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(dt, {
                                title: "Number",
                                digit: Object(Ke.a)({}, t.battery.text.imageNumber),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.battery.text.imageNumber = e, a.battery.text.enabled = a.battery.text.imageNumber.enabled || a.battery.text.shortcut.enabled, n(a)
                                },
                                followDisabled: !0,
                                showDataType: !1,
                                showDelimiter: !1,
                                showPrefix: !1
                            }), Object(Qe.jsx)(rt, {
                                ar: i
                            }), Object(Qe.jsx)(lt, {
                                title: "Icon",
                                image: Object(Ke.a)({}, t.battery.icon),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.battery.icon = e, n(a)
                                }
                            }), Object(Qe.jsx)(bt, {
                                title: "Shortcut",
                                shortcut: Object(Ke.a)({}, t.battery.text.shortcut),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.battery.text.shortcut = e, a.battery.text.enabled = a.battery.text.imageNumber.enabled || a.battery.text.shortcut.enabled, n(a)
                                }
                            }), Object(Qe.jsx)(mt, {
                                title: "Image set",
                                imageSet: Object(Ke.a)({}, t.battery.imageProgress),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.battery.imageProgress = e, n(a)
                                }
                            }), Object(Qe.jsx)(ut, {
                                title: "Icon set",
                                iconSet: Object(Ke.a)({}, t.battery.iconSetProgress),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.battery.iconSetProgress = e, n(a)
                                }
                            }), Object(Qe.jsx)(ht, {
                                title: "Pointer scale",
                                scale: Object(Ke.a)({}, t.battery.scale),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.battery.scale = e, n(a)
                                }
                            })]
                        })]
                    })
                },
                Yt = function(e) {
                    e.title;
                    var t = e.shortcut,
                        n = e.onUpdate,
                        i = e.onDelete,
                        o = e.disableIcon,
                        s = Object(a.useMemo)((function() {
                            var e, n, a, i, o, s;
                            return [{
                                blocks: [{
                                    title: "X",
                                    type: _e.Number,
                                    nvalue: (null === (e = t.Element) || void 0 === e ? void 0 : e.TopLeftX) ? t.Element.TopLeftX : 0,
                                    onChange: r
                                }, {
                                    title: "Y",
                                    type: _e.Number,
                                    nvalue: (null === (n = t.Element) || void 0 === n ? void 0 : n.TopLeftY) ? t.Element.TopLeftY : 0,
                                    onChange: l
                                }, {
                                    title: "Width",
                                    type: _e.Number,
                                    nvalue: (null === (a = t.Element) || void 0 === a ? void 0 : a.BottomRightX) ? (null === (i = t.Element) || void 0 === i ? void 0 : i.BottomRightX) - t.Element.TopLeftX : 0,
                                    onChange: d
                                }, {
                                    title: "Height",
                                    type: _e.Number,
                                    nvalue: (null === (o = t.Element) || void 0 === o ? void 0 : o.BottomRightY) ? (null === (s = t.Element) || void 0 === s ? void 0 : s.BottomRightY) - t.Element.TopLeftY : 0,
                                    onChange: c
                                }]
                            }]
                        }), [t]);

                    function r(e) {
                        var a = Object(Ke.a)({}, t);
                        a.Element.TopLeftX = e, n(a)
                    }

                    function l(e) {
                        var a = Object(Ke.a)({}, t);
                        a.Element.TopLeftY = e, n(a)
                    }

                    function d(e) {
                        var a = Object(Ke.a)({}, t);
                        a.Element.BottomRightX = a.Element.TopLeftX ? a.Element.TopLeftX + e : e, n(a)
                    }

                    function c(e) {
                        var a = Object(Ke.a)({}, t);
                        a.Element.BottomRightY = a.Element.TopLeftY ? a.Element.TopLeftY + e : e, n(a)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsxs)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            children: ["Shortcut: ", t.ShortcutType, Object(Qe.jsx)("button", {
                                className: "btn btn-outline-danger",
                                type: "button",
                                onClick: i,
                                children: "Delete"
                            })]
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            children: [o ? "" : Object(Qe.jsx)(lt, {
                                title: "Icon",
                                image: new le(t.Icon),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.Icon = e.json, n(a)
                                }
                            }), Object(Qe.jsx)(rt, {
                                ar: s
                            })]
                        })]
                    })
                },
                Ht = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface,
                        i = Object(a.useState)(f.Workout.json),
                        o = Object(r.a)(i, 2),
                        s = o[0],
                        l = o[1];
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsxs)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.shortcuts.collapsed = !e.shortcuts.collapsed, n(e)
                            },
                            children: ["Shortcuts", Object(Qe.jsxs)("span", {
                                className: "d-flex flex-nowrap",
                                children: [Object(Qe.jsx)("select", {
                                    className: "form-select form-control-sm",
                                    onChange: function(e) {
                                        return l(e.target.value)
                                    },
                                    onClick: function(e) {
                                        return e.stopPropagation()
                                    },
                                    value: s,
                                    children: Object.keys(f).map((function(e) {
                                        return f[e] instanceof p ? Object(Qe.jsx)("option", {
                                            value: f[e].json,
                                            children: f[e].json
                                        }, f[e].index) : ""
                                    }))
                                }), Object(Qe.jsx)("button", {
                                    className: "btn btn-outline-success btn-sm",
                                    type: "button",
                                    onClick: function() {
                                        var e = Object(Ke.a)({}, t),
                                            a = new E;
                                        a.Icon = new O, a.Element = new N, a.ShortcutType = s, e.shortcuts.json || (e.shortcuts.json = []), e.shortcuts.json.push(a), e.shortcuts.collapsed = !0, n(e)
                                    },
                                    children: "Add"
                                })]
                            })]
                        }), t.shortcuts.collapsed ? "" : Object(Qe.jsx)(ze.a.Body, {
                            children: t.shortcuts.json.length > 0 ? t.shortcuts.json.map((function(e, a) {
                                return Object(Qe.jsx)(Yt, {
                                    title: e.ShortcutType,
                                    shortcut: e,
                                    onUpdate: function(e) {
                                        return function(e, a) {
                                            var i = Object(Ke.a)({}, t);
                                            i.shortcuts.json[e] = a, n(i)
                                        }(a, e)
                                    },
                                    onDelete: function() {
                                        return function(e) {
                                            if (window.confirm("Would you delete shortcut " + t.shortcuts.json[e].ShortcutType)) {
                                                var a = Object(Ke.a)({}, t);
                                                a.shortcuts.json.splice(e, 1), n(a)
                                            }
                                        }(a)
                                    }
                                })
                            })) : "no shortcuts added"
                        })]
                    })
                },
                Ut = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.time.sunset.collapsed = !t.time.sunset.collapsed, n(e)
                            },
                            children: "Sunrise / Sunset"
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            className: "".concat(t.time.sunset.collapsed ? "collapse" : ""),
                            children: [Object(Qe.jsx)(dt, {
                                title: "Sunrise OneLine",
                                digit: Object(Ke.a)({}, t.time.sunset.sunriseOneLine),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.sunset.sunriseOneLine = e, n(a)
                                },
                                followDisabled: !0,
                                showDelimiter: !0,
                                showPrefix: !0,
                                paddingDisabled: !0
                            }), Object(Qe.jsx)(lt, {
                                title: "Sunrise icon",
                                image: Object(Ke.a)({}, t.time.sunset.sunsetIcon),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.sunset.sunriseIcon = e, n(a)
                                }
                            }), Object(Qe.jsx)(bt, {
                                title: "Sunrise shortcut",
                                shortcut: Object(Ke.a)({}, t.time.sunset.sunsetShortcut),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.sunset.sunriseShortcut = e, n(a)
                                }
                            }), Object(Qe.jsx)(dt, {
                                title: "Sunset OneLine",
                                digit: Object(Ke.a)({}, t.time.sunset.sunsetOneLine),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.sunset.sunsetOneLine = e, n(a)
                                },
                                followDisabled: !0,
                                showDelimiter: !0,
                                showPrefix: !0,
                                paddingDisabled: !0
                            }), Object(Qe.jsx)(lt, {
                                title: "Sunset icon",
                                image: Object(Ke.a)({}, t.time.sunset.sunsetIcon),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.sunset.sunsetIcon = e, n(a)
                                }
                            }), Object(Qe.jsx)(bt, {
                                title: "Sunset shortcut",
                                shortcut: Object(Ke.a)({}, t.time.sunset.sunsetShortcut),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.sunset.sunsetShortcut = e, n(a)
                                }
                            })]
                        })]
                    })
                },
                Bt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.time.timeDigitalSeparated.collapsed = !t.time.timeDigitalSeparated.collapsed, n(e)
                            },
                            children: "Time Separate Digits"
                        }), Object(Qe.jsxs)(ze.a.Body, {
                            className: "".concat(t.time.timeDigitalSeparated.collapsed ? "collapse" : ""),
                            children: [Object(Qe.jsx)(rt, {
                                ar: [{
                                    blocks: [{
                                        title: "Padding Zero Hours",
                                        type: _e.Checkbox,
                                        checked: t.time.timeDigitalSeparated.paddingZeroHours,
                                        onChange: function(e) {
                                            var a = Object(Ke.a)({}, t);
                                            a.time.timeDigitalSeparated.paddingZeroHours = e, n(a)
                                        }
                                    }, {
                                        title: "Padding Zero Minutes",
                                        type: _e.Checkbox,
                                        checked: t.time.timeDigitalSeparated.paddingZeroMinutes,
                                        onChange: function(e) {
                                            var a = Object(Ke.a)({}, t);
                                            a.time.timeDigitalSeparated.paddingZeroMinutes = e, n(a)
                                        }
                                    }]
                                }]
                            }), Object(Qe.jsx)(yt, {
                                title: "Hours Digits",
                                digit: Object(Ke.a)({}, t.time.timeDigitalSeparated.hours),
                                amountOfDigits: 2,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeDigitalSeparated.hours = e, n(a)
                                }
                            }), Object(Qe.jsx)(yt, {
                                title: "Minutes Digits",
                                digit: Object(Ke.a)({}, t.time.timeDigitalSeparated.minutes),
                                amountOfDigits: 2,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeDigitalSeparated.minutes = e, n(a)
                                }
                            }), Object(Qe.jsx)(yt, {
                                title: "Seconds Digits",
                                digit: Object(Ke.a)({}, t.time.timeDigitalSeparated.seconds),
                                amountOfDigits: 2,
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeDigitalSeparated.seconds = e, n(a)
                                }
                            }), Object(Qe.jsx)(lt, {
                                title: "Separator hours",
                                image: Object(Ke.a)({}, t.time.timeDigitalSeparated.separatorHours),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeDigitalSeparated.separatorHours = e, n(a)
                                }
                            }), Object(Qe.jsx)(lt, {
                                title: "Separator minutes",
                                image: Object(Ke.a)({}, t.time.timeDigitalSeparated.separatorMinutes),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.time.timeDigitalSeparated.separatorMinutes = e, n(a)
                                }
                            })]
                        })]
                    })
                },
                Xt = function(e) {
                    var t = e.title,
                        n = e.temp,
                        i = e.onUpdate,
                        o = Object(a.useMemo)((function() {
                            return [{
                                blocks: [{
                                    title: "Minus",
                                    type: _e.SelectFile,
                                    nvalue: n.minus,
                                    onChange: s
                                }, {
                                    title: "NoData",
                                    type: _e.SelectFile,
                                    nvalue: n.nodata,
                                    onChange: r
                                }, {
                                    title: "Suffix",
                                    type: _e.SelectFile,
                                    nvalue: n.suffix,
                                    onChange: l
                                }]
                            }]
                        }), [n]);

                    function s(e) {
                        var t = Object(Ke.a)({}, n);
                        t.minus = e, i(t)
                    }

                    function r(e) {
                        var t = Object(Ke.a)({}, n);
                        n.nodata = e, i(t)
                    }

                    function l(e) {
                        i(Object(Ke.a)(Object(Ke.a)({}, n), {}, {
                            suffix: e
                        }))
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: t
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: n.enabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, n);
                                            e.enabled = !e.enabled, e.watchNumber && (e.watchNumber.enabled = e.enabled), i(e)
                                        }
                                    })
                                })]
                            })
                        }), n.enabled ? Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(dt, {
                                title: "ImageNumber",
                                digit: Object(Ke.a)({}, n.watchNumber),
                                onUpdate: function(e) {
                                    i(Object(Ke.a)(Object(Ke.a)({}, n), {}, {
                                        watchNumber: Object(Ke.a)({}, e)
                                    }))
                                },
                                followDisabled: !0
                            }), Object(Qe.jsx)(rt, {
                                ar: o
                            })]
                        }) : ""]
                    })
                },
                Rt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface,
                        i = Object(a.useMemo)((function() {
                            return [{
                                blocks: [{
                                    title: "Minus",
                                    type: _e.SelectFile,
                                    nvalue: t.weather.oneLineMinus,
                                    onChange: o
                                }, {
                                    title: "Delimiter",
                                    type: _e.SelectFile,
                                    nvalue: t.weather.oneLineDelimiter,
                                    onChange: s
                                }, {
                                    title: "Degrees",
                                    type: _e.SelectFile,
                                    nvalue: t.weather.oneLineDegrees,
                                    onChange: r
                                }]
                            }]
                        }), [t.weather]);

                    function o(e) {
                        var a = Object(Ke.a)({}, t);
                        a.weather.oneLineMinus = e, n(a)
                    }

                    function s(e) {
                        var a = Object(Ke.a)({}, t);
                        a.weather.oneLineDelimiter = e, n(a)
                    }

                    function r(e) {
                        var a = Object(Ke.a)({}, t);
                        a.weather.oneLineDegrees = e, n(a)
                    }
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.weather.collapsed = !e.weather.collapsed, n(e)
                            },
                            children: "Weather"
                        }), t.weather.collapsed ? "" : Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(mt, {
                                title: "Icon",
                                imageSet: Object(Ke.a)({}, t.weather.icon),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weather.icon = e, n(a)
                                }
                            }), Object(Qe.jsx)(Xt, {
                                title: "Current",
                                temp: Object(Ke.a)({}, t.weather.current),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weather.current = e, n(a)
                                }
                            }), Object(Qe.jsx)(Xt, {
                                title: "Lowest",
                                temp: Object(Ke.a)({}, t.weather.lowest),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weather.lowest = e, n(a)
                                }
                            }), Object(Qe.jsx)(Xt, {
                                title: "Highest",
                                temp: Object(Ke.a)({}, t.weather.highest),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weather.highest = e, n(a)
                                }
                            }), Object(Qe.jsx)(dt, {
                                title: "One line min/max",
                                digit: Object(Ke.a)({}, t.weather.oneLineMinMax),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weather.oneLineMinMax = e, n(a)
                                },
                                followDisabled: !0
                            }), t.weather.oneLineMinMax.enabled ? Object(Qe.jsx)(ze.a, {
                                children: Object(Qe.jsx)(rt, {
                                    ar: i
                                })
                            }) : ""]
                        })]
                    })
                },
                Ft = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.weatherext.collapsedAirQuality = !e.weatherext.collapsedAirQuality, n(e)
                            },
                            children: "Air Quality"
                        }), t.weatherext.collapsedAirQuality ? "" : Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(dt, {
                                title: "Text",
                                digit: Object(Ke.a)({}, t.weatherext.airQualityNumber),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weatherext.airQualityNumber = e, n(a)
                                },
                                followDisabled: !0
                            }), Object(Qe.jsx)(lt, {
                                title: "Icon",
                                image: Object(Ke.a)({}, t.weatherext.airQualityIcon),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weatherext.airQualityIcon = e, n(a)
                                }
                            })]
                        })]
                    })
                },
                Wt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.weatherext.collapsedHumidity = !e.weatherext.collapsedHumidity, n(e)
                            },
                            children: "Humidity"
                        }), t.weatherext.collapsedHumidity ? "" : Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(dt, {
                                title: "Text",
                                digit: Object(Ke.a)({}, t.weatherext.humidityNumber),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weatherext.humidityNumber = e, n(a)
                                },
                                followDisabled: !0
                            }), t.weatherext.humidityNumber.enabled ? Object(Qe.jsx)(rt, {
                                ar: [{
                                    blocks: [{
                                        title: "Suffix",
                                        type: _e.SelectFile,
                                        nvalue: t.weatherext.humiditySuffix,
                                        onChange: function(e) {
                                            var a = Object(Ke.a)({}, t);
                                            a.weatherext.humiditySuffix = e, n(a)
                                        }
                                    }]
                                }]
                            }) : "", Object(Qe.jsx)(lt, {
                                title: "Icon",
                                image: Object(Ke.a)({}, t.weatherext.humidityIcon),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weatherext.humidityIcon = e, n(a)
                                }
                            }), Object(Qe.jsx)(mt, {
                                title: "Image progress",
                                imageSet: Object(Ke.a)({}, t.weatherext.humidityProgress.imageProgress),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weatherext.humidityProgress.imageProgress = e, n(a)
                                }
                            })]
                        })]
                    })
                },
                Zt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.weatherext.collapsedUvIndex = !e.weatherext.collapsedUvIndex, n(e)
                            },
                            children: "UV Index"
                        }), t.weatherext.collapsedUvIndex ? "" : Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(dt, {
                                title: "Text",
                                digit: Object(Ke.a)({}, t.weatherext.uvNumber),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weatherext.uvNumber = e, n(a)
                                },
                                followDisabled: !0
                            }), t.weatherext.uvNumber.enabled ? Object(Qe.jsx)(rt, {
                                ar: [{
                                    blocks: [{
                                        title: "Suffix",
                                        type: _e.SelectFile,
                                        nvalue: t.weatherext.uvSuffixImageIndex,
                                        onChange: function(e) {
                                            var a = Object(Ke.a)({}, t);
                                            a.weatherext.uvSuffixImageIndex = e, n(a)
                                        }
                                    }]
                                }]
                            }) : "", Object(Qe.jsx)(lt, {
                                title: "Icon",
                                image: Object(Ke.a)({}, t.weatherext.uvIcon),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weatherext.uvIcon = e, n(a)
                                }
                            }), Object(Qe.jsx)(mt, {
                                title: "Image progress",
                                imageSet: Object(Ke.a)({}, t.weatherext.uvProgress.imageProgress),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weatherext.uvProgress.imageProgress = e, n(a)
                                }
                            }), Object(Qe.jsx)(bt, {
                                title: "UV Shortcut",
                                shortcut: Object(Ke.a)({}, t.weatherext.uvShortcut),
                                onUpdate: function(e) {
                                    var a = Object(Ke.a)({}, t);
                                    a.weatherext.uvShortcut = e, n(a)
                                }
                            })]
                        })]
                    })
                },
                Gt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.setWatchface;
                    return Object(Qe.jsxs)(ze.a, {
                        className: "activity w-100",
                        children: [Object(Qe.jsx)(ze.a.Header, {
                            className: "d-flex justify-content-between align-items-center",
                            onClick: function() {
                                var e = Object(Ke.a)({}, t);
                                e.weatherext.collapsed = !e.weatherext.collapsed, n(e)
                            },
                            children: "Weather Additional"
                        }), t.weatherext.collapsed ? "" : Object(Qe.jsxs)(ze.a.Body, {
                            children: [Object(Qe.jsx)(Ft, {}), Object(Qe.jsx)(Wt, {}), Object(Qe.jsx)(Zt, {})]
                        })]
                    })
                },
                Jt = function() {
                    return Object(Qe.jsxs)(Qe.Fragment, {
                        children: [Object(Qe.jsx)(St, {}), Object(Qe.jsx)(Tt, {}), Object(Qe.jsx)(Bt, {}), Object(Qe.jsx)(Pt, {}), Object(Qe.jsx)(At, {}), Object(Qe.jsx)(Ut, {}), Object(Qe.jsx)(Dt, {}), Object(Qe.jsx)(Ct, {}), Object(Qe.jsx)(kt, {}), Object(Qe.jsx)(Mt, {}), Object(Qe.jsx)(Et, {}), Object(Qe.jsx)(Rt, {}), Object(Qe.jsx)(Gt, {}), Object(Qe.jsx)(Ht, {}), Object(Qe.jsx)(Lt, {})]
                    })
                },
                _t = function e() {
                    Object(h.a)(this, e)
                };
            _t.ar = ["Unknown weather", "Cloudy", "Shower", "Snow shower", "Sunny", "Overcast", "Light rain", "Light snow", "Moderate rain", "Moderate snow", "Heavy snow", "Heavy rain", "Sandstorm", "Sleet", "Fog", "Haze", "Thundershower", "Snowstorm", "Dust", "Extraordinary rainstorm", "Freezing rain", "Thundershowers with hail", "Heavy rainstorm", "Sand blowing", "Strong sandstorm", "Rainstorm"];
            var Qt = function() {
                    var e, t = Object(a.useContext)(m),
                        n = t.watchface,
                        i = t.watchState,
                        o = t.setWatchState;
                    Object(a.useEffect)((function() {
                        var e, t = Object(Ke.a)({}, i);
                        if ((null === (e = n.animation) || void 0 === e ? void 0 : e.imageSetAnimation) && n.animation.imageSetAnimation.length > 0) {
                            if (i.animation.length > n.animation.imageSetAnimation.length) t.animation.splice(n.animation.imageSetAnimation.length - 1), o(t);
                            else if (i.animation.length < n.animation.imageSetAnimation.length) {
                                for (var a = i.animation.length; a < n.animation.imageSetAnimation.length; a++) t.animation.push(0);
                                o(t)
                            }
                        } else t.animation = [], o(t)
                    }), [n]);
                    var s = Object(a.useMemo)((function() {
                            return "".concat(i.year.toString().padStart(4, "0"), "-").concat(i.month.toString().padStart(2, "0"), "-").concat(i.day.toString().padStart(2, "0"))
                        }), [i]),
                        l = Object(a.useMemo)((function() {
                            return "".concat(i.hours.toString().padStart(2, "0"), ":").concat(i.minutes.toString().padStart(2, "0"), ":").concat(i.seconds.toString().padStart(2, "0"))
                        }), [i]),
                        d = Object(a.useMemo)((function() {
                            return "".concat(i.alarmHours.toString().padStart(2, "0"), ":").concat(i.alarmMinutes.toString().padStart(2, "0"))
                        }), [i]);
                    return Object(Qe.jsx)("div", {
                        children: Object(Qe.jsxs)(Qe.Fragment, {
                            children: [Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Date"
                                }), Object(Qe.jsx)("input", {
                                    type: "date",
                                    className: "form-control form-control-sm",
                                    value: s,
                                    onChange: function(e) {
                                        var t = new Date(e.target.value),
                                            n = Object(Ke.a)({}, i);
                                        n.year = t.getFullYear(), n.month = t.getMonth() + 1, n.monthasword = t.getMonth(), n.day = t.getDate(), n.weekday = t.getDay() > 0 ? t.getDay() - 1 : 6, o(n)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Time"
                                }), Object(Qe.jsx)("input", {
                                    type: "time",
                                    className: "form-control form-control-sm",
                                    step: "1",
                                    value: l,
                                    onChange: function(e) {
                                        var t = e.target.value.split(":"),
                                            n = Object(r.a)(t, 3),
                                            a = n[0],
                                            s = n[1],
                                            l = n[2],
                                            d = Object(Ke.a)({}, i);
                                        isNaN(parseInt(a)) || (d.hours = parseInt(a)), isNaN(parseInt(s)) || (d.minutes = parseInt(s)), isNaN(parseInt(l)) || (d.seconds = parseInt(l)), o(d)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    id: "addon-wrapping",
                                    children: "Alarm"
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: i.alarmEnabled,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, i);
                                            e.alarmEnabled = !e.alarmEnabled, o(e)
                                        }
                                    })
                                }), Object(Qe.jsx)("input", {
                                    type: "time",
                                    className: "form-control form-control-sm",
                                    step: "1",
                                    value: d,
                                    onChange: function(e) {
                                        var t = e.target.value.split(":"),
                                            n = Object(r.a)(t, 2),
                                            a = n[0],
                                            s = n[1],
                                            l = Object(Ke.a)({}, i);
                                        isNaN(parseInt(a)) || (l.alarmHours = parseInt(a)), isNaN(parseInt(s)) || (l.alarmMinutes = parseInt(s)), o(l)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Sunrise"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "23",
                                    value: i.sunriseHours,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.sunriseHours = isNaN(n) ? 0 : Math.min(n, 23), o(t)
                                    }
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "59",
                                    value: i.sunriseMinutes,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.sunriseMinutes = isNaN(n) ? 0 : Math.min(n, 23), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Sunset"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "23",
                                    value: i.sunsetHours,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.sunsetHours = isNaN(n) ? 0 : Math.min(n, 23), o(t)
                                    }
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "59",
                                    value: i.sunsetMinutes,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.sunsetMinutes = isNaN(n) ? 0 : Math.min(n, 23), o(t)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Battery"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "100",
                                    value: i.battery,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.battery = isNaN(n) ? 0 : Math.min(n, 100), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Calories"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "9999",
                                    value: i.calories,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.calories = isNaN(n) ? 0 : Math.min(n, 9999), o(t)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Steps"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "99999",
                                    value: i.steps,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.steps = isNaN(n) ? 0 : Math.min(n, 99999), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Steps Goal"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "99999",
                                    value: i.stepsGoal,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.stepsGoal = isNaN(n) ? 0 : Math.min(n, 99999), o(t)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Hearthrate"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: i.hearthrateGoal,
                                    value: i.hearthrate,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.hearthrate = isNaN(n) ? 0 : Math.min(n, i.hearthrateGoal), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Distance"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "9999",
                                    value: i.distance,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.distance = isNaN(n) ? 0 : Math.min(n, 9999), o(t)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "PAI"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: i.paiGoal,
                                    value: i.pai,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.pai = isNaN(n) ? 0 : Math.min(n, i.paiGoal), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "StandUp"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: i.standupGoal,
                                    value: i.standup,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.standup = isNaN(n) ? 0 : Math.min(n, i.standupGoal), o(t)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Stress"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "999",
                                    value: i.stress,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.stress = isNaN(n) ? 0 : Math.min(n, 999), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Fat Burning"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "99",
                                    value: i.fatBurning,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.fatBurning = isNaN(n) ? 0 : Math.min(n, 99), o(t)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Weather Icon"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "25",
                                    value: i.weatherIcon,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.weatherIcon = isNaN(n) ? 0 : Math.min(n, ae.imageProgressTotal), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: _t.ar[i.weatherIcon]
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Current"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "-99",
                                    max: "99",
                                    value: i.temperature,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.temperature = isNaN(n) ? 0 : Math.max(Math.min(n, 99), -99), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Min"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "-99",
                                    max: "99",
                                    value: i.temperatureMin,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.temperatureMin = isNaN(n) ? 0 : Math.max(Math.min(n, 99), -99), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Max"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "-99",
                                    max: "99",
                                    value: i.temperatureMax,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.temperatureMax = isNaN(n) ? 0 : Math.max(Math.min(n, 99), -99), o(t)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "UV Index"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "11",
                                    value: i.uvIndex,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.uvIndex = isNaN(n) ? 0 : Math.min(n, 11), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Air Quality"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "500",
                                    value: i.airQuality,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.airQuality = isNaN(n) ? 0 : Math.min(n, 500), o(t)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm mb-1",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Humidity"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "100",
                                    value: i.humidity,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.humidity = isNaN(n) ? 0 : Math.min(n, 100), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Windforce"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: "12",
                                    value: i.windForce,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.windForce = isNaN(n) ? 0 : Math.min(n, 12), o(t)
                                    }
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    children: "Air Pressure"
                                }), Object(Qe.jsx)("input", {
                                    type: "number",
                                    className: "form-control form-control-sm",
                                    min: "0",
                                    max: i.airPressureGoal,
                                    value: i.airPressure,
                                    onChange: function(e) {
                                        var t = Object(Ke.a)({}, i),
                                            n = parseInt(e.target.value);
                                        t.airPressure = isNaN(n) ? 0 : Math.min(n, i.airPressureGoal), o(t)
                                    }
                                })]
                            }), Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    id: "addon-wrapping",
                                    children: "Blutooth"
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: i.bluetooth,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, i);
                                            e.bluetooth = !e.bluetooth, o(e)
                                        }
                                    })
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    id: "addon-wrapping",
                                    children: "DnD"
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: i.dnd,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, i);
                                            e.dnd = !e.dnd, o(e)
                                        }
                                    })
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    id: "addon-wrapping",
                                    children: "Alarm"
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: i.alarm,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, i);
                                            e.alarm = !e.alarm, o(e)
                                        }
                                    })
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    id: "addon-wrapping",
                                    children: "Lock"
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: i.lock,
                                        onChange: function() {
                                            var e = Object(Ke.a)({}, i);
                                            e.lock = !e.lock, o(e)
                                        }
                                    })
                                })]
                            }), Object(Qe.jsxs)(ze.a, {
                                className: "mt-3",
                                children: [Object(Qe.jsx)(ze.a.Header, {
                                    children: Object(Qe.jsx)("h3", {
                                        children: "Preview of animations"
                                    })
                                }), Object(Qe.jsx)(ze.a.Body, {
                                    children: (null === (e = i.animation) || void 0 === e ? void 0 : e.length) > 0 ? i.animation.map((function(e, t) {
                                        var a, s, r;
                                        return Object(Qe.jsxs)("div", {
                                            className: "input-group input-group-sm mb-1",
                                            children: [Object(Qe.jsxs)("span", {
                                                className: "input-group-text",
                                                children: ["Animation ", t + 1, ". Frame for preview "]
                                            }), Object(Qe.jsx)("input", {
                                                type: "number",
                                                className: "form-control form-control-sm",
                                                value: e + 1,
                                                min: 1,
                                                max: null === (a = n.animation) || void 0 === a || null === (s = a.imageSetAnimation[t]) || void 0 === s || null === (r = s.ImageProgress) || void 0 === r ? void 0 : r.ImagesCount,
                                                onChange: function(e) {
                                                    var n = Object(Ke.a)({}, i),
                                                        a = parseInt(e.target.value);
                                                    n.animation[t] = isNaN(a) ? 0 : Math.max(0, a - 1), o(n)
                                                }
                                            })]
                                        }, t)
                                    })) : "no animation in watchface"
                                })]
                            })]
                        })
                    })
                },
                Vt = [{
                    id: 0,
                    name: "Screen normal",
                    el: Object(Qe.jsx)("div", {
                        className: "mt-3 blocks",
                        children: Object(Qe.jsx)(Jt, {})
                    })
                }, {
                    id: 1,
                    name: "AOD",
                    el: Object(Qe.jsx)("div", {
                        className: "mt-3 blocks",
                        children: Object(Qe.jsx)(wt, {})
                    })
                }, {
                    id: 2,
                    name: "Preview State",
                    el: Object(Qe.jsx)("div", {
                        className: "mt-3",
                        children: Object(Qe.jsx)(Qt, {})
                    })
                }],
                Kt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.setPreviewScreenNormal,
                        n = e.device,
                        i = Object(a.useState)(0),
                        o = Object(r.a)(i, 2),
                        s = o[0],
                        l = o[1];
                    return Object(Qe.jsxs)("div", {
                        children: [Object(Qe.jsxs)("ul", {
                            className: "nav nav-tabs",
                            children: [Object(Qe.jsx)("span", {
                                className: "navbar-brand mb-0 h1",
                                children: n.title
                            }), Vt.map((function(e) {
                                return Object(Qe.jsx)("li", {
                                    className: "nav-item",
                                    children: Object(Qe.jsx)("button", {
                                        className: "nav-link ".concat(s === e.id ? "active" : "", " "),
                                        onClick: function() {
                                            return n = e.id, l(n), 0 === n && t(!0), void(1 === n && t(!1));
                                            var n
                                        },
                                        children: e.name
                                    })
                                }, e.id)
                            }))]
                        }), Vt[s].el]
                    })
                },
                zt = n(14),
                $t = n.n(zt),
                qt = function() {
                    var e = Object(a.useContext)(m),
                        t = e.watchface,
                        n = e.jsonName,
                        i = e.device,
                        o = Object(a.useState)(""),
                        s = Object(r.a)(o, 2),
                        l = s[0],
                        d = s[1];
                    return Object(a.useEffect)((function() {
                        var e = function(e) {
                            var t, n, a = e.time.timeAnalog.hours.enabled || e.time.timeAnalog.minutes.enabled || e.time.timeAnalog.seconds.enabled,
                                o = {
                                    Info: {
                                        DeviceId: i.deviceId
                                    },
                                    Background: gn(e.background),
                                    TimeExtended: en(e.time),
                                    Activity: dn(e.activity),
                                    DateBlock: tn(e.date),
                                    Weather: sn(e.weather, e.weatherext),
                                    StepProgress: an(e.activity.steps.aProgress),
                                    Status: rn(e.status),
                                    Battery: ln(e.battery),
                                    Animation: (null === (t = e.animation) || void 0 === t || null === (n = t.imageSetAnimation) || void 0 === n ? void 0 : n.length) > 0 ? {
                                        ImageSetAnimation: e.animation.imageSetAnimation
                                    } : null,
                                    HeartProgress: an(e.activity.heartRate.aProgress),
                                    CaloriesProgress: an(e.activity.calories.aProgress),
                                    HumidityProgress: an(e.weatherext.humidityProgress),
                                    Alarm: cn(e.time.alarm),
                                    Shortcuts: un(e.shortcuts),
                                    TimeAnalog: a ? {
                                        CommonCenterCoordinates: e.time.timeAnalog.commonCenterCoordinates,
                                        Hours: e.time.timeAnalog.hours.enabled ? e.time.timeAnalog.hours.json : null,
                                        Minutes: e.time.timeAnalog.minutes.enabled ? e.time.timeAnalog.minutes.json : null,
                                        Seconds: e.time.timeAnalog.seconds.enabled ? e.time.timeAnalog.seconds.json : null
                                    } : null,
                                    HourlyImages: null,
                                    TimeDigital: on(e.time.timeDigitalCommon),
                                    PaiProgress: an(e.activity.pai.aProgress),
                                    StandUpProgress: an(e.activity.standUp.aProgress),
                                    UviProgress: an(e.weatherext.uvProgress),
                                    AlwaysOnDisplay: hn(e.aod),
                                    ActivitySeparateDigits: bn(e.activity)
                                };
                            return JSON.stringify(o, (function(e, t) {
                                if (null !== t && void 0 !== t) return t
                            }), "  ")
                        }(t);
                        d(e),
                            function(e) {
                                if (e.length > 0) {
                                    var t = document.getElementById("saveJson");
                                    if (t) {
                                        var a = new Blob([e], {
                                                type: "text/plain"
                                            }),
                                            i = n || "watchface.json";
                                        t.href = URL.createObjectURL(a), t.download = i
                                    }
                                }
                            }(e)
                    }), [t]), Object(Qe.jsxs)(Qe.Fragment, {
                        children: [Object(Qe.jsx)(ze.a, {
                            className: $t.a.json,
                            children: Object(Qe.jsx)("pre", {
                                children: l
                            })
                        }), Object(Qe.jsx)("br", {}), Object(Qe.jsx)("a", {
                            href: "a",
                            id: "saveJson",
                            children: "download json file"
                        })]
                    })
                };

            function en(e) {
                var t, n, a, i, o, s, r, l, d, c, u, m, h, g, b, j = e.timeDigitalSeparated.hours.enabled || e.timeDigitalSeparated.minutes.enabled || e.timeDigitalSeparated.seconds.enabled,
                    p = e.sunset.sunriseOneLine.enabled || e.sunset.sunriseOneLine.enabled || e.sunset.sunsetIcon.enabled || e.sunset.sunriseIcon.enabled || e.sunset.sunsetShortcut.enabled || e.sunset.sunriseShortcut.enabled;
                return j || p ? {
                    TimeSeparateDigits: j ? {
                        Hours: (null === e || void 0 === e || null === (t = e.timeDigitalSeparated) || void 0 === t ? void 0 : t.hours.enabled) ? null === e || void 0 === e || null === (n = e.timeDigitalSeparated) || void 0 === n || null === (a = n.hours) || void 0 === a ? void 0 : a.json : null,
                        Minutes: (null === e || void 0 === e || null === (i = e.timeDigitalSeparated) || void 0 === i ? void 0 : i.minutes.enabled) ? null === e || void 0 === e || null === (o = e.timeDigitalSeparated) || void 0 === o || null === (s = o.minutes) || void 0 === s ? void 0 : s.json : null,
                        Seconds: (null === e || void 0 === e || null === (r = e.timeDigitalSeparated) || void 0 === r ? void 0 : r.seconds.enabled) ? null === e || void 0 === e || null === (l = e.timeDigitalSeparated) || void 0 === l || null === (d = l.seconds) || void 0 === d ? void 0 : d.json : null,
                        SeparatorHours: (null === e || void 0 === e || null === (c = e.timeDigitalSeparated) || void 0 === c ? void 0 : c.separatorHours.enabled) ? null === e || void 0 === e || null === (u = e.timeDigitalSeparated) || void 0 === u ? void 0 : u.separatorHours.json : null,
                        SeparatorMinutes: (null === e || void 0 === e || null === (m = e.timeDigitalSeparated) || void 0 === m ? void 0 : m.separatorMinutes.enabled) ? null === e || void 0 === e || null === (h = e.timeDigitalSeparated) || void 0 === h ? void 0 : h.separatorMinutes.json : null,
                        PaddingZeroHours: null === e || void 0 === e || null === (g = e.timeDigitalSeparated) || void 0 === g ? void 0 : g.paddingZeroHours,
                        PaddingZeroMinutes: null === e || void 0 === e || null === (b = e.timeDigitalSeparated) || void 0 === b ? void 0 : b.paddingZeroMinutes
                    } : null,
                    SunsetTimeOneLine: e.sunset.sunsetOneLine.enabled ? e.sunset.sunsetOneLine.json : null,
                    DelimiterSunsetImageIndex: e.sunset.sunsetOneLine.enabled ? e.sunset.sunsetOneLine.delimiter : null,
                    SunriseTimeOneLine: e.sunset.sunriseOneLine.enabled ? e.sunset.sunriseOneLine.json : null,
                    DelimiterSunriseImageIndex: e.sunset.sunriseOneLine.enabled ? e.sunset.sunriseOneLine.delimiter : null,
                    SunsetIcon: e.sunset.sunsetIcon.enabled ? e.sunset.sunsetIcon.json : null,
                    SunriseIcon: e.sunset.sunriseIcon.enabled ? e.sunset.sunriseIcon.json : null,
                    SunsetShortcut: e.sunset.sunsetShortcut.enabled ? e.sunset.sunsetShortcut.json : null,
                    SunriseShortcut: e.sunset.sunriseShortcut.enabled ? e.sunset.sunriseShortcut.json : null,
                    SunsetImageIndex: e.sunset.sunsetOneLine.enabled ? e.sunset.sunsetOneLine.prefix : null,
                    SunriseImageIndex: e.sunset.sunriseOneLine.enabled ? e.sunset.sunriseOneLine.prefix : null
                } : null
            }

            function tn(e) {
                var t = e.day.enabled || e.month.enabled || e.monthAsWord.enabled || e.year.enabled;
                return t || e.weekday.enabled || e.ampm.enabled ? {
                    Date: t ? nn(e) : null,
                    AmPm: e.ampm.enabled ? e.ampm.json : null,
                    Unknown3: null,
                    Weekday: e.weekday.enabled ? e.weekday.json : null,
                    WeekdayChinese: e.weekday.enabled ? e.weekday.json : null,
                    WeekdayTradChinese: e.weekday.enabled ? e.weekday.json : null,
                    WeekdayProgress: an(e.weekdayProgress)
                } : null
            }

            function nn(e) {
                var t, n, a, i, o, s, r, l, d, c, u, m, h, g, b, j, p, v, f, x, O, y, I, w, C, S, D, N, M, P;
                return {
                    MonthAndDayAlt: null,
                    OneLineMonthAndDay: e.oneLineMonth ? {
                        Number: e.month.enabled ? e.month.json : null,
                        DelimiterImageIndex: e.oneLineDelimiter
                    } : null,
                    OneLineYearMonthAndDay: e.oneLineYear ? {
                        Number: e.year.enabled ? e.year.json : null,
                        DelimiterImageIndex: e.oneLineDelimiter
                    } : null,
                    PaddingZeroMonth: e.oneLineYear ? null === (t = e.year) || void 0 === t ? void 0 : t.paddingZero : !!(null === (n = e.month) || void 0 === n ? void 0 : n.paddingZero),
                    PaddingZeroDay: e.oneLineYear ? null === (a = e.year) || void 0 === a ? void 0 : a.paddingZero : e.oneLineMonth ? null === (i = e.month) || void 0 === i ? void 0 : i.paddingZero : !!(null === (o = e.day) || void 0 === o ? void 0 : o.paddingZero),
                    UnknownBoolean6: !1,
                    YearMonthAndDay: e.oneLineYear || e.oneLineMonth ? null : {
                        Year: (null === (s = e.year) || void 0 === s ? void 0 : s.enabled) ? e.year.json : null,
                        Month: (null === (r = e.month) || void 0 === r ? void 0 : r.enabled) ? e.month.json : null,
                        Day: (null === (l = e.day) || void 0 === l ? void 0 : l.enabled) ? e.day.json : null,
                        MonthFollowsYear: !!(null === (d = e.month) || void 0 === d ? void 0 : d.follow),
                        DayFollowsMonth: !!(null === (c = e.day) || void 0 === c ? void 0 : c.follow),
                        MonthAsWord: (null === (u = e.monthAsWord) || void 0 === u ? void 0 : u.enabled) ? e.monthAsWord.json : null,
                        MonthAsWordChinese: (null === (m = e.monthAsWord) || void 0 === m ? void 0 : m.enabled) ? e.monthAsWord.json : null,
                        YearDataTypeImageIndex: (null === (h = e.year) || void 0 === h ? void 0 : h.enabled) ? null === (g = e.year) || void 0 === g ? void 0 : g.dataType : null,
                        MonthDataTypeImageIndex: (null === (b = e.month) || void 0 === b ? void 0 : b.enabled) ? null === (j = e.month) || void 0 === j ? void 0 : j.dataType : null,
                        DayDataTypeImageIndex: (null === (p = e.day) || void 0 === p ? void 0 : p.enabled) ? null === (v = e.day) || void 0 === v ? void 0 : v.dataType : null,
                        DelimiterYearImageIndex: (null === (f = e.year) || void 0 === f ? void 0 : f.enabled) ? null === (x = e.year) || void 0 === x ? void 0 : x.delimiter : null,
                        DelimiterMonthImageIndex: (null === (O = e.month) || void 0 === O ? void 0 : O.enabled) ? null === (y = e.month) || void 0 === y ? void 0 : y.delimiter : null,
                        DelimiterDayImageIndex: (null === (I = e.day) || void 0 === I ? void 0 : I.enabled) ? null === (w = e.day) || void 0 === w ? void 0 : w.delimiter : null,
                        DelimiterYearCoordinates: (null === (C = e.year) || void 0 === C ? void 0 : C.enabled) && (null === (S = e.year) || void 0 === S ? void 0 : S.delimiter) ? e.year.delimiterCoords : null,
                        DelimiterMonthCoordinates: (null === (D = e.month) || void 0 === D ? void 0 : D.enabled) && (null === (N = e.month) || void 0 === N ? void 0 : N.delimiter) ? e.month.delimiterCoords : null,
                        DelimiterDayCoordinates: (null === (M = e.day) || void 0 === M ? void 0 : M.enabled) && (null === (P = e.day) || void 0 === P ? void 0 : P.delimiter) ? e.day.delimiterCoords : null
                    }
                }
            }

            function an(e) {
                return e.circleScale.enabled || e.iconSetProgress.enabled || e.imageProgress.enabled || e.scale.enabled || e.noDataImage.enabled ? {
                    ImageProgress: e.imageProgress.enabled ? e.imageProgress.json : null,
                    IconSetProgress: e.iconSetProgress.enabled ? e.iconSetProgress.json : null,
                    CircleScale: e.circleScale.enabled ? e.circleScale.json : null,
                    Scale: e.scale.enabled ? {
                        PointerScale: e.scale.pointerScaleJson,
                        BottomImage: e.scale.bottomImage.enabled ? e.scale.bottomImage.json : null,
                        BottomImageChinese: e.scale.bottomImage.enabled ? e.scale.bottomImage.json : null,
                        BottomImageTradChinese: e.scale.bottomImage.enabled ? e.scale.bottomImage.json : null
                    } : null,
                    NoDataImage: e.noDataImage.enabled ? e.noDataImage.json : null,
                    UnknownImage: null
                } : null
            }

            function on(e) {
                return e.hours.enabled || e.minutes.enabled || e.seconds.enabled ? {
                    Hours: e.hours.enabled ? e.hours.json : null,
                    HoursDataTypeImageIndex: e.hours.dataType,
                    PaddingZeroHours: e.hours.paddingZero,
                    DelimiterHoursImageIndex: e.hours.delimiter,
                    DelimiterMinutesImageIndex: e.minutes.delimiter,
                    HoursFollowPosition: !1,
                    DelimiterSecondsImageIndex: e.seconds.delimiter,
                    Time: e.minutes.enabled || e.seconds.enabled ? {
                        Unknown1: e.time_unknown1,
                        Minutes: e.minutes.enabled ? e.minutes.json : null,
                        Seconds: e.seconds.enabled ? e.seconds.json : null,
                        PaddingZeroMinutes: e.minutes.paddingZero,
                        PaddingZeroSeconds: e.seconds.paddingZero,
                        MinutesDataTypeImageIndex: e.minutes.enabled ? e.minutes.dataType : null,
                        SecondsDataTypeImageIndex: e.seconds.enabled ? e.seconds.dataType : null,
                        MinutesFollowHours: e.minutes.follow,
                        SecondsFollowMinutes: e.seconds.follow,
                        HoursDataTypeCoordinates: e.hours.enabled && e.hours.dataType ? e.hours.delimiterCoords : null,
                        MinutesDataTypeCoordinates: e.minutes.enabled && !e.minutes.follow && e.minutes.dataType ? e.minutes.delimiterCoords : null,
                        SecondsDataTypeCoordinates: e.seconds.enabled && !e.seconds.follow && e.seconds.dataType ? e.seconds.delimiterCoords : null
                    } : null
                } : null
            }

            function sn(e, t) {
                var n = e.icon.enabled,
                    a = e.current.enabled || e.oneLineMinMax.enabled || e.lowest.enabled || e.highest.enabled,
                    i = t.airQualityNumber.enabled || t.airQualityIcon.enabled,
                    o = t.humidityNumber.enabled || t.humidityIcon.enabled,
                    s = t.uvNumber.enabled || t.uvIcon.enabled || t.uvShortcut.enabled;
                return n || a || i || o || s ? {
                    Icon: n ? {
                        Images: e.icon.json
                    } : null,
                    Temperature: a ? {
                        Current: e.current.enabled ? {
                            ImageNumber: e.current.watchNumber.enabled ? e.current.watchNumber.json : null,
                            MinusImageIndex: e.current.minus,
                            SuffixImageIndexC: e.current.suffix,
                            SuffixImageIndexF: e.current.suffix,
                            NoDataImageIndex: e.current.nodata,
                            Shortcut: e.current.shortcut.enabled ? e.current.shortcut.json : null
                        } : null,
                        OneLine: e.oneLineMinMax.enabled ? {
                            OneLineMinMax: {
                                Number: e.oneLineMinMax.enabled ? e.oneLineMinMax.json : null,
                                MinusImageIndex: e.oneLineMinus,
                                DelimiterImageIndex: e.oneLineDelimiter,
                                UnknownLong4: 0,
                                DegreesImageIndex: e.oneLineDegrees
                            }
                        } : null,
                        Lowest: e.lowest.enabled ? {
                            ImageNumber: e.lowest.watchNumber.enabled ? e.lowest.watchNumber.json : null,
                            MinusImageIndex: e.lowest.minus,
                            SuffixImageIndexC: e.lowest.suffix,
                            SuffixImageIndexF: e.lowest.suffix,
                            NoDataImageIndex: e.lowest.nodata,
                            Shortcut: e.lowest.shortcut.enabled ? e.lowest.shortcut.json : null
                        } : null,
                        Highest: e.highest.enabled ? {
                            ImageNumber: e.highest.watchNumber.enabled ? e.highest.watchNumber.json : null,
                            MinusImageIndex: e.highest.minus,
                            SuffixImageIndexC: e.highest.suffix,
                            SuffixImageIndexF: e.highest.suffix,
                            NoDataImageIndex: e.highest.nodata,
                            Shortcut: e.highest.shortcut.enabled ? e.highest.shortcut.json : null
                        } : null
                    } : null,
                    AirQuality: i ? {
                        AirQualityNumber: t.airQualityNumber.enabled ? t.airQualityNumber.json : null,
                        AirQualityIcon: t.airQualityIcon.enabled ? t.airQualityIcon.json : null
                    } : null,
                    Humidity: o ? {
                        HumidityNumber: t.humidityNumber.enabled ? t.humidityNumber.json : null,
                        SuffixImageIndex: t.humiditySuffix,
                        HumidityIcon: t.humidityIcon.enabled ? t.humidityIcon.json : null
                    } : null,
                    UVindex: s ? {
                        UVindexNumber: t.uvNumber.enabled ? t.uvNumber.json : null,
                        SuffixImageIndex: t.uvSuffixImageIndex,
                        Shortcut: t.uvShortcut.enabled ? t.uvShortcut.json : null,
                        UVindexIcon: t.uvIcon.enabled ? t.uvIcon.json : null
                    } : null
                } : null
            }

            function rn(e) {
                return e.alarm.enabled || e.bluetooth.enabled || e.lock.enabled || e.doNotDisturb.enabled ? {
                    DoNotDisturb: e.doNotDisturb.enabled ? e.doNotDisturb.json : null,
                    Lock: e.lock.enabled ? e.lock.json : null,
                    Bluetooth: e.bluetooth.enabled ? e.bluetooth.json : null,
                    Alarm: e.alarm.enabled ? e.alarm.json : null
                } : null
            }

            function ln(e) {
                return e.text.enabled || e.imageProgress.enabled || e.iconSetProgress.enabled || e.scale.enabled || e.icon.enabled ? {
                    BatteryText: e.text.enabled ? {
                        ImageNumber: e.text.imageNumber.enabled ? e.text.imageNumber.json : null,
                        PrefixImageIndex: e.text.prefix,
                        NoDataImageIndex: e.text.noData,
                        Icon: e.text.icon.enabled ? e.text.icon.json : null,
                        Shortcut: e.text.shortcut.enabled ? e.text.shortcut.json : null,
                        SuffixImageIndex: e.text.suffix,
                        SuffixImageCoordinates: e.text.suffixImageCoordinates,
                        DecimalPointImageIndex: null,
                        SuffixKMImageIndex: null,
                        SuffixMIImageIndex: null
                    } : null,
                    ImageProgress: e.imageProgress.enabled ? e.imageProgress.json : null,
                    IconSetProgress: e.iconSetProgress.enabled ? e.iconSetProgress.json : null,
                    Scale: e.scale.enabled ? {
                        PointerScale: e.scale.pointerScaleJson,
                        BottomImage: e.scale.bottomImage.enabled ? e.scale.bottomImage.json : null,
                        BottomImageChinese: e.scale.bottomImage.enabled ? e.scale.bottomImage.json : null,
                        BottomImageTradChinese: e.scale.bottomImage.enabled ? e.scale.bottomImage.json : null
                    } : null,
                    Icon: e.icon.enabled ? e.icon.json : null
                } : null
            }

            function dn(e) {
                return e.steps.aElement.enabled || e.calories.aElement.enabled || e.heartRate.aElement.enabled || e.distance.aElement.enabled || e.pai.aElement.enabled || e.standUp.aElement.enabled ? {
                    Steps: e.steps.aElement.enabled ? {
                        ImageNumber: e.steps.aElement.imageNumber.enabled ? e.steps.aElement.imageNumber.json : null,
                        PrefixImageIndex: e.steps.aElement.prefix,
                        NoDataImageIndex: e.steps.aElement.noData,
                        Icon: e.steps.aElement.icon.enabled ? e.steps.aElement.icon.json : null,
                        Shortcut: e.steps.aElement.shortcut.enabled ? e.steps.aElement.shortcut.json : null,
                        SuffixImageIndex: e.steps.aElement.suffix,
                        SuffixImageCoordinates: e.steps.aElement.suffixImageCoordinates,
                        DecimalPointImageIndex: null,
                        SuffixKMImageIndex: null,
                        SuffixMIImageIndex: null
                    } : null,
                    Calories: e.calories.aElement.enabled ? {
                        ImageNumber: e.calories.aElement.imageNumber.enabled ? e.calories.aElement.imageNumber.json : null,
                        PrefixImageIndex: e.calories.aElement.prefix,
                        NoDataImageIndex: e.calories.aElement.noData,
                        Icon: e.calories.aElement.icon.enabled ? e.calories.aElement.icon.json : null,
                        Shortcut: e.calories.aElement.shortcut.enabled ? e.calories.aElement.shortcut.json : null,
                        SuffixImageIndex: e.calories.aElement.suffix,
                        SuffixImageCoordinates: e.calories.aElement.suffixImageCoordinates,
                        DecimalPointImageIndex: null,
                        SuffixKMImageIndex: null,
                        SuffixMIImageIndex: null
                    } : null,
                    HeartRate: e.heartRate.aElement.enabled ? {
                        ImageNumber: e.heartRate.aElement.imageNumber.enabled ? e.heartRate.aElement.imageNumber.json : null,
                        PrefixImageIndex: e.heartRate.aElement.prefix,
                        NoDataImageIndex: e.heartRate.aElement.noData,
                        Icon: e.heartRate.aElement.icon.enabled ? e.heartRate.aElement.icon.json : null,
                        Shortcut: e.heartRate.aElement.shortcut.enabled ? e.heartRate.aElement.shortcut.json : null,
                        SuffixImageIndex: e.heartRate.aElement.suffix,
                        SuffixImageCoordinates: e.heartRate.aElement.suffixImageCoordinates,
                        DecimalPointImageIndex: null,
                        SuffixKMImageIndex: null,
                        SuffixMIImageIndex: null
                    } : null,
                    Distance: e.distance.aElement.enabled ? {
                        ImageNumber: e.distance.aElement.imageNumber.enabled ? e.distance.aElement.imageNumber.json : null,
                        PrefixImageIndex: e.distance.aElement.prefix,
                        NoDataImageIndex: e.distance.aElement.noData,
                        Icon: e.distance.aElement.icon.enabled ? e.distance.aElement.icon.json : null,
                        Shortcut: e.distance.aElement.shortcut.enabled ? e.distance.aElement.shortcut.json : null,
                        SuffixImageIndex: e.distance.aElement.suffix,
                        SuffixImageCoordinates: null,
                        DecimalPointImageIndex: e.distance.aElement.decimalPoint,
                        SuffixKMImageIndex: e.distance.aElement.suffixKM,
                        SuffixMIImageIndex: e.distance.aElement.suffixMI
                    } : null,
                    PAI: e.pai.aElement.enabled ? {
                        ImageNumber: e.pai.aElement.imageNumber.enabled ? e.pai.aElement.imageNumber.json : null,
                        PrefixImageIndex: e.pai.aElement.prefix,
                        NoDataImageIndex: e.pai.aElement.noData,
                        Icon: e.pai.aElement.icon.enabled ? e.pai.aElement.icon.json : null,
                        Shortcut: e.pai.aElement.shortcut.enabled ? e.pai.aElement.shortcut.json : null,
                        SuffixImageIndex: e.pai.aElement.suffix,
                        SuffixImageCoordinates: e.pai.aElement.suffixImageCoordinates,
                        DecimalPointImageIndex: null,
                        SuffixKMImageIndex: null,
                        SuffixMIImageIndex: null
                    } : null,
                    UnknownLongValue7: 0,
                    StandUp: e.standUp.aElement.enabled ? {
                        ImageNumber: e.standUp.aElement.imageNumber.enabled ? e.standUp.aElement.imageNumber.json : null,
                        PrefixImageIndex: e.standUp.aElement.prefix,
                        NoDataImageIndex: e.standUp.aElement.noData,
                        Icon: e.standUp.aElement.icon.enabled ? e.standUp.aElement.icon.json : null,
                        Shortcut: e.standUp.aElement.shortcut.enabled ? e.standUp.aElement.shortcut.json : null,
                        SuffixImageIndex: e.standUp.aElement.suffix,
                        SuffixImageCoordinates: e.standUp.aElement.suffixImageCoordinates,
                        DecimalPointImageIndex: null,
                        SuffixKMImageIndex: null,
                        SuffixMIImageIndex: null
                    } : null
                } : null
            }

            function cn(e) {
                return e.noAlarm.enabled || e.alarmImage.enabled || e.shortcut.enabled || e.alarmTime.hours.enabled || e.alarmTime.minutes.enabled ? {
                    NoAlarmImage: e.noAlarm.enabled ? e.noAlarm.json : null,
                    AlarmImage: e.alarmImage.enabled ? e.alarmImage.json : null,
                    ShortcutArea: e.shortcut.enabled ? e.shortcut.json : null,
                    AlarmTime: e.alarmTime.hours.enabled || e.alarmTime.minutes.enabled ? {
                        Hours: e.alarmTime.hours.enabled ? e.alarmTime.hours.json : null,
                        Minutes: e.alarmTime.minutes.enabled ? e.alarmTime.minutes.json : null,
                        DataTypeHoursImageIndex: e.alarmTime.hours.enabled ? e.alarmTime.hours.dataType : null,
                        DelimiterHoursImageIndex: e.alarmTime.hours.enabled ? e.alarmTime.hours.delimiter : null,
                        DelimiterMinutesImageIndex: e.alarmTime.minutes.enabled ? e.alarmTime.minutes.delimiter : null,
                        PaddingZeroHours: e.alarmTime.hours.enabled ? e.alarmTime.hours.paddingZero : null,
                        PaddingZeroMinutes: e.alarmTime.minutes.enabled ? e.alarmTime.minutes.paddingZero : null,
                        DataTypeHoursCoordinates: e.alarmTime.hours.enabled && e.alarmTime.hours.dataType ? e.alarmTime.hours.delimiterCoords : null,
                        MinutesFollowHours: e.alarmTime.minutes.enabled ? e.alarmTime.minutes.follow : null
                    } : null
                } : null
            }

            function un(e) {
                return e.json && e.json.length > 0 ? {
                    Shortcut: e.json.map((function(e) {
                        var t;
                        return {
                            Icon: (null === (t = e.Icon) || void 0 === t ? void 0 : t.ImageIndex) >= 0 ? e.Icon : null,
                            ShortcutType: e.ShortcutType,
                            Element: e.Element
                        }
                    }))
                } : null
            }

            function mn(e) {
                var t, n, a = e.timeSeparateDigits.hours.enabled || e.timeSeparateDigits.minutes.enabled,
                    i = e.timeAnalog.hours.enabled || e.timeAnalog.minutes.enabled,
                    o = e.timeDigital.hours.enabled || e.timeDigital.minutes.enabled,
                    s = e.amPm.enabled;
                return s || i || o || a ? {
                    TimeSeparateDigits: a ? {
                        Hours: e.timeSeparateDigits.hours.enabled ? e.timeSeparateDigits.hours.json : null,
                        Minutes: e.timeSeparateDigits.minutes.enabled ? e.timeSeparateDigits.minutes.json : null,
                        Separator: e.timeSeparateDigits.separator.enabled ? e.timeSeparateDigits.separator.json : null,
                        PaddingZeroHours: e.timeSeparateDigits.hours.enabled ? !!e.timeSeparateDigits.paddingZero : null
                    } : null,
                    TimeAnalog: i ? {
                        CommonCenterCoordinates: e.timeAnalog.commonCenterCoordinates ? e.timeAnalog.commonCenterCoordinates : null,
                        Hours: e.timeAnalog.hours.enabled ? {
                            ImageIndex: e.timeAnalog.hours.json.ImageIndex,
                            CenterCoordinates: null,
                            PointerCenterOfRotationY: e.timeAnalog.hours.json.PointerCenterOfRotationY,
                            CoverImage: (null === (t = e.timeAnalog.hours.json.CoverImage) || void 0 === t ? void 0 : t.ImageIndex) ? e.timeAnalog.hours.json.CoverImage : null
                        } : null,
                        Minutes: e.timeAnalog.minutes.enabled ? {
                            ImageIndex: e.timeAnalog.minutes.json.ImageIndex,
                            CenterCoordinates: null,
                            PointerCenterOfRotationY: e.timeAnalog.minutes.json.PointerCenterOfRotationY,
                            CoverImage: (null === (n = e.timeAnalog.minutes.json.CoverImage) || void 0 === n ? void 0 : n.ImageIndex) ? e.timeAnalog.minutes.json.CoverImage : null
                        } : null
                    } : null,
                    AmPm: s ? e.amPm.json : null,
                    TimeDigital: o ? {
                        Hours: e.timeDigital.hours.enabled ? e.timeDigital.hours.json : null,
                        Minutes: e.timeDigital.minutes.enabled ? e.timeDigital.minutes.json : null,
                        HoursDataTypeImageIndex: e.timeDigital.hours.enabled ? e.timeDigital.hours.dataType : null,
                        MinutesDataTypeImageIndex: e.timeDigital.minutes.enabled ? e.timeDigital.minutes.dataType : null,
                        DelimiterHoursImageIndex: e.timeDigital.hours.enabled ? e.timeDigital.hours.delimiter : null,
                        DelimiterMinutesImageIndex: e.timeDigital.minutes.enabled ? e.timeDigital.minutes.delimiter : null,
                        PaddingZeroHours: e.timeDigital.hours.enabled ? !!e.timeDigital.hours.paddingZero : null,
                        PaddingZeroMinutes: e.timeDigital.minutes.enabled ? !!e.timeDigital.minutes.paddingZero : null,
                        MinutesFollowHours: e.timeDigital.minutes.enabled ? !!e.timeDigital.minutes.follow : null,
                        DataTypeHoursCoordinates: e.timeDigital.hours.enabled ? e.timeDigital.hours.delimiterCoords : null,
                        DataTypeMinutesCoordinates: e.timeDigital.minutes.enabled ? e.timeDigital.minutes.delimiterCoords : null
                    } : null
                } : null
            }

            function hn(e) {
                var t = e.time.timeSeparateDigits.hours.enabled || e.time.timeSeparateDigits.minutes.enabled,
                    n = e.time.timeAnalog.hours.enabled || e.time.timeAnalog.minutes.enabled,
                    a = e.time.timeDigital.hours.enabled || e.time.timeDigital.minutes.enabled,
                    i = e.time.amPm.enabled || n || a || t,
                    o = e.date.day.enabled || e.date.month.enabled,
                    s = e.dateOneLine.monthAndDay.enabled;
                return i || o || s || e.steps.aElement.enabled || e.weekday.enabled ? {
                    TimeExtended: i ? mn(e.time) : null,
                    DateOneLine: e.dateOneLine.monthAndDay.enabled ? {
                        MonthAndDay: e.dateOneLine.monthAndDay.json,
                        SeparatorImageIndex: e.dateOneLine.separatorImageIndex
                    } : null,
                    Week: e.weekday.enabled ? {
                        Weekday: e.weekday.json,
                        WeekdayChinese: null,
                        WeekdayTradChinese: null
                    } : null,
                    Steps: e.steps.aElement.enabled ? {
                        ImageNumber: e.steps.aElement.imageNumber.enabled ? e.steps.aElement.imageNumber.json : null,
                        PrefixImageIndex: e.steps.aElement.prefix,
                        NoDataImageIndex: e.steps.aElement.noData,
                        Icon: e.steps.aElement.icon.enabled ? e.steps.aElement.icon.json : null,
                        Shortcut: e.steps.aElement.shortcut.enabled ? e.steps.aElement.shortcut.json : null,
                        SuffixImageIndex: e.steps.aElement.suffix,
                        SuffixImageCoordinates: e.steps.aElement.suffixImageCoordinates,
                        DecimalPointImageIndex: null,
                        SuffixKMImageIndex: null,
                        SuffixMIImageIndex: null
                    } : null,
                    Date: o ? {
                        Month: e.date.month.enabled ? e.date.month.json : null,
                        Day: e.date.day.enabled ? e.date.day.json : null,
                        MonthDataTypeImageIndex: e.date.month.enabled ? e.date.month.dataType : null,
                        DayDataTypeImageIndex: e.date.day.enabled ? e.date.day.dataType : null,
                        DelimiterMonthImageIndex: e.date.month.enabled ? e.date.month.delimiter : null,
                        DelimiterDayImageIndex: e.date.day.enabled ? e.date.day.delimiter : null,
                        PaddingZeroMonth: !!e.date.month.enabled && !!e.date.month.paddingZero,
                        PaddingZeroDay: !!e.date.day.enabled && !!e.date.day.paddingZero,
                        DelimiterMonthCoordinates: e.date.month.enabled ? e.date.month.delimiterCoords : null,
                        DelimiterDayCoordinates: e.date.day.enabled ? e.date.day.delimiterCoords : null,
                        DayFollowsMonth: e.date.day.follow
                    } : null
                } : null
            }

            function gn(e) {
                return e.color || e.floatingLayer.enabled || e.image.enabled || e.preview.enabled ? {
                    Image: e.image.enabled ? e.image.json : null,
                    BackgroundColor: !e.image.enabled && e.color ? e.color : null,
                    Preview: e.preview.enabled ? e.preview.json : null,
                    PreviewChinese: e.previewc.enabled ? e.previewc.json : null,
                    PreviewTradChinese: e.previewtradchin.enabled ? e.previewtradchin.json : null,
                    FloatingLayer: e.floatingLayer.enabled ? e.floatingLayer.json : null
                } : null
            }

            function bn(e) {
                return e.stepsSeparatedDigits.enabled || e.caloriesSeparatedDigits.enabled || e.heartRateSeparatedDigits.enabled || e.batterySeparatedDigits.enabled ? {
                    Calories: e.caloriesSeparatedDigits.enabled ? e.caloriesSeparatedDigits.json : null,
                    Steps: e.stepsSeparatedDigits.enabled ? e.stepsSeparatedDigits.json : null,
                    Battery: e.batterySeparatedDigits.enabled ? e.batterySeparatedDigits.json : null,
                    HeartRate: e.heartRateSeparatedDigits.enabled ? e.heartRateSeparatedDigits.json : null
                } : null
            }

            function jn(e, t) {
                if (null === e || void 0 === e) return null;
                var n = t.find((function(t) {
                    return t.id === e
                }));
                return n ? n.image : (console.error("Image with Index  " + e + " not found"), null)
            }

            function pn(e, t, n, a, i) {
                if (null !== i) {
                    var o = n.Width ? n.Width : 0,
                        s = n.CenterX ? n.CenterX : 0,
                        r = n.CenterY ? n.CenterY : 0;
                    a > i && (a = i);
                    var l = n.StartAngle ? n.StartAngle : 0,
                        d = l + a * ((n.EndAngle ? n.EndAngle : 360) - l) / i,
                        c = n.RadiusX;
                    if (n.ImageIndex) {
                        var u = jn(n.ImageIndex, t);
                        u && (e.save(), e.beginPath(), function(e, t, n, a, i, o, s, r) {
                            if (r < 3) return;
                            if (180 === t) {
                                var l = n + s * Math.cos(Math.PI * (i - 90) / 180),
                                    d = a + s * Math.sin(Math.PI * (i - 90) / 180),
                                    c = n + s * Math.cos(Math.PI * (o - 90) / 180),
                                    u = a + s * Math.sin(Math.PI * (o - 90) / 180),
                                    m = Math.PI / 180 * (i - 90),
                                    h = Math.PI / 180 * (o - 90),
                                    g = m < h;
                                e.arc(n, a, s - r / 2, m, h, !g), e.arc(l, d, r / 2, m - Math.PI, m, !g), e.arc(n, a, s + r / 2, m, h, !g), e.arc(c, u, r / 2, h, h + Math.PI, !g)
                            } else if (90 === t) {
                                var b = Math.PI / 180 * (i - 90),
                                    j = Math.PI / 180 * (o - 90),
                                    p = b < j,
                                    v = n + (s - r / 2) * Math.cos(Math.PI * (i - 90) / 180),
                                    f = a + (s - r / 2) * Math.sin(Math.PI * (i - 90) / 180),
                                    x = n + s * Math.cos(Math.PI * (i - (p ? 1 : -1) * (r / 2 * 360 / (2 * Math.PI * (s - r / 2))) - 90) / 180),
                                    O = a + s * Math.sin(Math.PI * (i - (p ? 1 : -1) * (r / 2 * 360 / (2 * Math.PI * (s - r / 2))) - 90) / 180),
                                    y = n + (s + r / 2) * Math.cos(Math.PI * (i - 90) / 180),
                                    I = a + (s + r / 2) * Math.sin(Math.PI * (i - 90) / 180),
                                    w = n + s * Math.cos(Math.PI * (o + (p ? 1 : -1) * r / 2 * 360 / (2 * Math.PI * (s - r / 2)) - 90) / 180),
                                    C = a + s * Math.sin(Math.PI * (o + (p ? 1 : -1) * r / 2 * 360 / (2 * Math.PI * (s - r / 2)) - 90) / 180),
                                    S = n + (s - r / 2) * Math.cos(Math.PI * (o - 90) / 180),
                                    D = a + (s - r / 2) * Math.sin(Math.PI * (o - 90) / 180);
                                e.arc(n, a, s - r / 2, b, j, !p), e.moveTo(v, f), e.lineTo(x, O), e.lineTo(y, I), e.arc(n, a, s + r / 2, b, j, !p), e.lineTo(w, C), e.lineTo(S, D)
                            } else {
                                var N = n + (s - r / 2) * Math.cos(Math.PI * (i - 90) / 180),
                                    M = a + (s - r / 2) * Math.sin(Math.PI * (i - 90) / 180),
                                    P = n + (s + r / 2) * Math.cos(Math.PI * (i - 90) / 180),
                                    T = a + (s + r / 2) * Math.sin(Math.PI * (i - 90) / 180),
                                    k = n + (s - r / 2) * Math.cos(Math.PI * (o - 90) / 180),
                                    A = a + (s - r / 2) * Math.sin(Math.PI * (o - 90) / 180),
                                    L = Math.PI / 180 * (i - 90),
                                    E = Math.PI / 180 * (o - 90),
                                    Y = L < E;
                                e.arc(n, a, s - r / 2, L, E, !Y), e.moveTo(N, M), e.lineTo(P, T), e.arc(n, a, s + r / 2, L, E, !Y), e.lineTo(k, A)
                            }
                        }(e, n.Flatness, s, r, l, d, c, o), e.clip(), e.drawImage(u, s - u.width / 2, r - u.height / 2), e.restore())
                    } else if (n.Color) {
                        var m = j.colorRead(n.Color);
                        if (j.GFG_Fun(m)) {
                            e.beginPath();
                            var h = Math.PI / 180 * (l - 90),
                                g = Math.PI / 180 * (d - 90),
                                b = h < g;
                            e.arc(s, r, c, h, g, !b), e.strokeStyle = m, e.lineWidth = o, e.stroke(),
                                function(e, t, n, a, i, o, s, r, l) {
                                    if (l < 3) return;
                                    if (180 === n) {
                                        var d = a + r * Math.cos(Math.PI * (o - 90) / 180),
                                            c = i + r * Math.sin(Math.PI * (o - 90) / 180);
                                        e.beginPath(), e.lineWidth = 1, e.arc(d, c, l / 2 - 1, 0, 2 * Math.PI), e.strokeStyle = t, e.fillStyle = t, e.stroke(), e.fill(), d = a + r * Math.cos(Math.PI * (s - 90) / 180), c = i + r * Math.sin(Math.PI * (s - 90) / 180), e.beginPath(), e.lineWidth = 1, e.arc(d, c, l / 2 - 1, 0, 2 * Math.PI), e.strokeStyle = t, e.fillStyle = t, e.stroke(), e.fill()
                                    } else if (90 === n) {
                                        var u = a + (r + l / 2) * Math.cos(Math.PI * (o - 90) / 180),
                                            m = i + (r + l / 2) * Math.sin(Math.PI * (o - 90) / 180),
                                            h = a + (r - l / 2) * Math.cos(Math.PI * (o - 90) / 180),
                                            g = i + (r - l / 2) * Math.sin(Math.PI * (o - 90) / 180),
                                            b = a + r * Math.cos(Math.PI * (o - l / 2 * 360 / (2 * Math.PI * (r - l / 2)) - 90) / 180),
                                            j = i + r * Math.sin(Math.PI * (o - l / 2 * 360 / (2 * Math.PI * (r - l / 2)) - 90) / 180);
                                        e.fillStyle = t, e.beginPath(), e.lineWidth = 1, e.moveTo(u, m), e.lineTo(h, g), e.lineTo(b, j), e.closePath(), e.fill(), u = a + (r + l / 2) * Math.cos(Math.PI * (s - 90) / 180), m = i + (r + l / 2) * Math.sin(Math.PI * (s - 90) / 180), h = a + (r - l / 2) * Math.cos(Math.PI * (s - 90) / 180), g = i + (r - l / 2) * Math.sin(Math.PI * (s - 90) / 180), b = a + r * Math.cos(Math.PI * (s + l / 2 * 360 / (2 * Math.PI * (r - l / 2)) - 90) / 180), j = i + r * Math.sin(Math.PI * (s + l / 2 * 360 / (2 * Math.PI * (r - l / 2)) - 90) / 180), e.fillStyle = t, e.beginPath(), e.lineWidth = 1, e.moveTo(u, m), e.lineTo(h, g), e.lineTo(b, j), e.closePath(), e.fill()
                                    }
                                }(e, m, n.Flatness, s, r, l, d, c, o), e.lineWidth = 1
                        }
                    }
                }
            }

            function vn(e, t, n, a, i) {
                var o, s, r, l, d, c, u, m, h = (null === (o = n.json) || void 0 === o ? void 0 : o.TopLeftX) ? null === (s = n.json) || void 0 === s ? void 0 : s.TopLeftX : 0,
                    g = (null === (r = n.json) || void 0 === r ? void 0 : r.TopLeftY) ? null === (l = n.json) || void 0 === l ? void 0 : l.TopLeftY : 0,
                    b = (null === (d = n.json) || void 0 === d ? void 0 : d.BottomRightX) ? null === (c = n.json) || void 0 === c ? void 0 : c.BottomRightX : h,
                    j = (null === (u = n.json) || void 0 === u ? void 0 : u.BottomRightY) ? null === (m = n.json) || void 0 === m ? void 0 : m.BottomRightY : g;
                if (n.json.ImageIndex) {
                    var p = [];
                    a.forEach((function(e, a) {
                        if (e.prefix) {
                            var i = jn(e.prefix, t);
                            i && p.push(i)
                        }
                        if (p = p.concat(On(t, e.snumber, n.json.ImageIndex, n.json.ImagesCount, null)), e.suffix) {
                            var o = jn(e.suffix, t);
                            o && p.push(o)
                        }
                        if (e.dataType) {
                            var s = jn(e.dataType, t);
                            s && p.push(s)
                        }
                    })), yn(e, p, h, g, b, j, n.json.Spacing, n.json.VerticalOffset, n.json.Alignment, i)
                }
            }

            function fn(e, t, n, a, i, o, s, r, l) {
                var d, c, u, m, h, g, b, j, p = (null === (d = n.json) || void 0 === d ? void 0 : d.TopLeftX) ? null === (c = n.json) || void 0 === c ? void 0 : c.TopLeftX : 0,
                    v = (null === (u = n.json) || void 0 === u ? void 0 : u.TopLeftY) ? null === (m = n.json) || void 0 === m ? void 0 : m.TopLeftY : 0,
                    f = (null === (h = n.json) || void 0 === h ? void 0 : h.BottomRightX) ? null === (g = n.json) || void 0 === g ? void 0 : g.BottomRightX : p,
                    x = (null === (b = n.json) || void 0 === b ? void 0 : b.BottomRightY) ? null === (j = n.json) || void 0 === j ? void 0 : j.BottomRightY : v;
                if (n.json.ImageIndex) {
                    var O = [],
                        y = null;
                    i && (y = jn(i, t));
                    var I = null;
                    r && (I = jn(r, t));
                    var w = null;
                    s && (w = jn(s, t)), I && O.push(I), a.forEach((function(e, i) {
                        O = O.concat(On(t, e, n.json.ImageIndex, n.json.ImagesCount, null, l)), y && i < a.length - 1 && O.push(y)
                    })), w && O.push(w), yn(e, O, p, v, f, x, n.json.Spacing, n.json.VerticalOffset, n.json.Alignment, o)
                }
            }

            function xn(e, t, n, a, i, o, s, r, l, d, c, u) {
                var m, h, g, b, j, p, v, f, x, O, y, I, w = i ? i[0] : (null === (m = n.json) || void 0 === m ? void 0 : m.TopLeftX) ? null === (h = n.json) || void 0 === h ? void 0 : h.TopLeftX : 0,
                    C = i ? i[1] : (null === (g = n.json) || void 0 === g ? void 0 : g.TopLeftY) ? null === (b = n.json) || void 0 === b ? void 0 : b.TopLeftY : 0,
                    S = i ? i[0] + ((null === (j = n.json) || void 0 === j ? void 0 : j.BottomRightX) - (null === (p = n.json) || void 0 === p ? void 0 : p.TopLeftX)) : (null === (v = n.json) || void 0 === v ? void 0 : v.BottomRightX) ? null === (f = n.json) || void 0 === f ? void 0 : f.BottomRightX : 0,
                    D = i ? i[1] + ((null === (x = n.json) || void 0 === x ? void 0 : x.BottomRightY) - (null === (O = n.json) || void 0 === O ? void 0 : O.TopLeftY)) : (null === (y = n.json) || void 0 === y ? void 0 : y.BottomRightY) ? null === (I = n.json) || void 0 === I ? void 0 : I.BottomRightY : 0;
                if (n.json.ImageIndex) {
                    var N = a.toString();
                    a < 0 && (N = (-a).toString()), (n.paddingZero || s) && (N = N.padStart(n.con.numberLenght, "0"));
                    var M = [];
                    if (l) {
                        var P = jn(l, t);
                        P && M.push(P)
                    }
                    if (a < 0 && r) {
                        var T = jn(r, t);
                        T && M.push(T)
                    }
                    if (M = M.concat(On(t, N, n.json.ImageIndex, n.json.ImagesCount, d)), d && u) {
                        var k = jn(u, t);
                        k && M.push(k)
                    } else if (c) {
                        var A = jn(c, t);
                        A && M.push(A)
                    }
                    return yn(e, M, w, C, S, D, n.json.Spacing, n.json.VerticalOffset, n.json.Alignment, o)
                }
                return i
            }

            function On(e, t, n, a, i, o) {
                for (var s = [], r = 0; r < t.length; r++) {
                    if (i && r === t.length - 2) {
                        var l = jn(i, e);
                        l && s.push(l)
                    }
                    var d = t.charAt(r);
                    if ("-" === d) {
                        if (o) {
                            var c = jn(o, e);
                            c && s.push(c)
                        }
                    } else {
                        var u = parseInt(d);
                        if (!isNaN(u) && u < a) {
                            var m = jn(n + u, e);
                            m && s.push(m)
                        }
                    }
                }
                return s
            }

            function yn(e, t, n, a, i, o, s, r, l, d) {
                if (0 !== t.length) {
                    s || (s = 0);
                    var c = 0,
                        u = 0,
                        m = a,
                        h = a,
                        g = a;
                    t.forEach((function(e, t) {
                        c += e.width, c += s, r ? (t > 0 && (g += r), m = Math.min(m, g), h = Math.max(h, g + e.height)) : e.height > u && (u = e.height)
                    })), c -= s, r && (u = h - m);
                    var b = i - n,
                        j = o - a,
                        p = n,
                        f = a;
                    return l === v.Right.json || l === v.TopRight.json || l === v.CenterRight.json || l === v.BottomRight.json ? p = p + b - c : l !== v.Center.json && l !== v.TopCenter.json && l !== v.BottomCenter.json || (p = p + b / 2 - c / 2), l === v.Bottom.json || l === v.BottomLeft.json || l === v.BottomCenter.json || l === v.BottomRight.json ? f = f + j - u : l !== v.Center.json && l !== v.CenterLeft.json && l !== v.CenterRight.json || (f = f + j / 2 - u / 2), t.forEach((function(t) {
                        e.drawImage(t, p, f), p += t.width, s && (p += s), r && (f += r)
                    })), d && (e.beginPath(), e.strokeStyle = "gray", e.rect(n, a, i - n, o - a), e.stroke()), [p, f]
                }
            }

            function In(e, t, n, a, i) {
                if ((null === n || void 0 === n ? void 0 : n.ImageIndex) && (null === n || void 0 === n ? void 0 : n.Coordinates)) {
                    var o;
                    a > i && (a = i);
                    var s = null === (o = n.Coordinates) || void 0 === o ? void 0 : o.length;
                    if (s) {
                        var r = Math.floor(a / (i / s));
                        r = Math.max(r, 0), r = Math.min(r, s - 1), console.log("iconset", a, i, s, r, n.ImageIndex + r, n.Coordinates[r].X, n.Coordinates[r].Y);
                        var l = jn(n.ImageIndex + r, t);
                        l && e.drawImage(l, n.Coordinates[r].X, n.Coordinates[r].Y)
                    }
                }
            }

            function wn(e, t, n) {
                if (null === n || void 0 === n ? void 0 : n.ImageIndex) {
                    var a = n.X ? n.X : 0,
                        i = n.Y ? n.Y : 0,
                        o = jn(n.ImageIndex, t);
                    o && e.drawImage(o, a, i)
                }
            }

            function Cn(e, t, n, a, i) {
                if (null === n || void 0 === n ? void 0 : n.ImageIndex) {
                    var o = n.X ? n.X : 0,
                        s = n.Y ? n.Y : 0;
                    a > i && (a = i);
                    var r = n.ImagesCount ? n.ImagesCount : 1,
                        l = Math.floor(a / (i / r));
                    l = Math.max(l, 0), l = Math.min(l, n.ImagesCount - 1);
                    var d = jn(n.ImageIndex + l, t);
                    d && e.drawImage(d, o, s)
                }
            }

            function Sn(e, t, n, a, i) {
                if (null !== i && (null === n || void 0 === n ? void 0 : n.PointerImageIndex) >= 0) {
                    var o, s;
                    o = n.CenterX ? n.CenterX : 0, s = n.CenterY ? n.CenterY : 0;
                    var r = jn(n.PointerImageIndex, t);
                    if (r) {
                        var l = r.width / 2,
                            d = n.PointerCenterOfRotationY ? n.PointerCenterOfRotationY : 0,
                            c = n.RangeFrom ? n.RangeFrom : 0;
                        a > i && (a = i);
                        var u = c + a * ((n.RangeTo ? n.RangeTo : 360) - c) / i,
                            m = Math.PI / 180 * u;
                        e.save(), e.translate(o, s), e.rotate(m), e.drawImage(r, -l, -d, r.width, r.height), e.restore()
                    }
                }
            }

            function Dn(e, t, n) {
                var a = t.TopLeftX ? t.TopLeftX : 0,
                    i = t.TopLeftY ? t.TopLeftY : 0,
                    o = t.BottomRightX ? t.BottomRightX : a,
                    s = t.BottomRightY ? t.BottomRightY : i;
                e.strokeStyle = "cyan", e.lineWidth = 1, n && e.strokeRect(a, i, o - a, s - i)
            }

            function Nn(e, t, n, a, i, o, s) {
                n && (n.aElement.enabled && xn(e, t, n.aElement.imageNumber, a, null, o, !1, null, n.aElement.prefix, n.aElement.decimalPoint, n.aElement.suffix, n.aElement.suffixKM), n.aElement.icon.enabled && wn(e, t, n.aElement.icon.json), n.aProgress.imageProgress.enabled && Cn(e, t, n.aProgress.imageProgress.json, a, i), n.aProgress.iconSetProgress.enabled && In(e, t, n.aProgress.iconSetProgress.json, a, i), n.aProgress.circleScale.enabled && pn(e, t, n.aProgress.circleScale.json, a, i), n.aProgress.scale.enabled && (n.aProgress.scale.bottomImage.enabled && wn(e, t, n.aProgress.scale.bottomImage.json), Sn(e, t, n.aProgress.scale.pointerScaleJson, a, i)), n.aElement.shortcut.enabled && Dn(e, n.aElement.shortcut.json, s))
            }

            function Mn(e, t, n, a, i) {
                if (n.Tens) {
                    var o = Math.floor(a / 10);
                    (a >= 10 || i) && Cn(e, t, n.Tens, o, 10)
                }
                n.Ones && Cn(e, t, n.Ones, a % 10, 10)
            }

            function Pn(e, t, n, a, i) {
                if (n.Ones) {
                    var o = Math.floor(a / 100);
                    (a >= 100 || i) && Cn(e, t, n.Ones, o, 10)
                }
                if (n.Tens) {
                    var s = Math.floor(a % 100 / 10);
                    (a >= 10 || i) && Cn(e, t, n.Tens, s, 10)
                }
                n.Hundreds && Cn(e, t, n.Hundreds, a % 100 % 10, 10)
            }

            function Tn(e, t, n, a) {
                if (a && n.ImageIndexOn) {
                    var i = n.Coordinates.X ? n.Coordinates.X : 0,
                        o = n.Coordinates.Y ? n.Coordinates.Y : 0,
                        s = jn(n.ImageIndexOn, t);
                    s && e.drawImage(s, i, o)
                }
                if (!a && n.ImageIndexOff) {
                    var r = n.Coordinates.X ? n.Coordinates.X : 0,
                        l = n.Coordinates.Y ? n.Coordinates.Y : 0,
                        d = jn(n.ImageIndexOff, t);
                    d && e.drawImage(d, r, l)
                }
            }

            function kn(e, t, n, a, i, o, s, r) {
                var l;
                if (null !== i) {
                    if (n.json.ImageIndex >= 0) {
                        var d, c, u, m, h, g, b = 0,
                            j = 0;
                        if (o) b = o.X ? o.X : 0, j = o.Y ? o.Y : 0;
                        else if (b = n.json.CenterCoordinates ? n.json.CenterCoordinates.X : 0, j = n.json.CenterCoordinates ? n.json.CenterCoordinates.Y : 0, !(null === (d = n.json.CenterCoordinates) || void 0 === d ? void 0 : d.X) && !(null === (c = n.json.CenterCoordinates) || void 0 === c ? void 0 : c.X)) b = (null === (u = n.json.CenterCoordinates) || void 0 === u ? void 0 : u.X) ? null === (m = n.json.CenterCoordinates) || void 0 === m ? void 0 : m.X : s / 2, j = (null === (h = n.json.CenterCoordinates) || void 0 === h ? void 0 : h.Y) ? null === (g = n.json.CenterCoordinates) || void 0 === g ? void 0 : g.X : r / 2;
                        var p = jn(n.json.ImageIndex, t);
                        if (p) {
                            var v = p.width / 2,
                                f = n.json.PointerCenterOfRotationY ? n.json.PointerCenterOfRotationY : 0;
                            a > i && (a = i);
                            var x = 0 + 360 * a / i,
                                O = Math.PI / 180 * x;
                            e.save(), e.translate(b, j), e.rotate(O), e.drawImage(p, -v, -f, p.width, p.height), e.restore()
                        }
                    }
                    if ((null === (l = n.json.CoverImage) || void 0 === l ? void 0 : l.ImageIndex) >= 0) {
                        var y, I, w = (null === (y = n.json.CoverImage) || void 0 === y ? void 0 : y.X) ? n.json.CoverImage.X : 0,
                            C = (null === (I = n.json.CoverImage) || void 0 === I ? void 0 : I.Y) ? n.json.CoverImage.Y : 0,
                            S = jn(n.json.CoverImage.ImageIndex, t);
                        S && e.drawImage(S, w, C)
                    }
                }
            }
            var An = n(15),
                Ln = function(e) {
                    var t = e.draw,
                        n = e.className,
                        i = Object(An.a)(e, ["draw", "className"]),
                        o = Object(a.useRef)(null);
                    return Object(a.useEffect)((function() {
                        var e = o.current,
                            n = e.getContext("2d");
                        t(e, n)
                    }), [t]), Object(Qe.jsx)("canvas", Object(Ke.a)({
                        className: n,
                        ref: o
                    }, i))
                },
                En = n(12),
                Yn = n.n(En),
                Hn = "preview_white_grid",
                Un = "preview_black_grid",
                Bn = "preview_digit_border",
                Xn = "preview_shortcut_border",
                Rn = function() {
                    var e = Object(a.useContext)(m),
                        t = e.images,
                        n = e.watchface,
                        i = e.watchState,
                        o = e.previewScreenNormal,
                        s = e.device,
                        l = Object(a.useState)(0),
                        d = Object(r.a)(l, 2),
                        c = d[0],
                        u = d[1],
                        h = Object(a.useState)(0),
                        g = Object(r.a)(h, 2),
                        b = g[0],
                        p = g[1],
                        v = Object(a.useState)(!!localStorage.getItem(Hn) && JSON.parse(localStorage.getItem(Hn))),
                        f = Object(r.a)(v, 2),
                        x = f[0],
                        O = f[1],
                        y = Object(a.useState)(!!localStorage.getItem(Un) && JSON.parse(localStorage.getItem(Un))),
                        I = Object(r.a)(y, 2),
                        w = I[0],
                        C = I[1],
                        S = Object(a.useState)(!!localStorage.getItem(Bn) && JSON.parse(localStorage.getItem(Bn))),
                        D = Object(r.a)(S, 2),
                        N = D[0],
                        M = D[1],
                        P = Object(a.useState)(!!localStorage.getItem(Xn) && JSON.parse(localStorage.getItem(Xn))),
                        T = Object(r.a)(P, 2),
                        k = T[0],
                        A = T[1];

                    function L(e, t, n) {
                        var a = arguments.length > 3 && void 0 !== arguments[3] ? arguments[3] : "black",
                            i = arguments.length > 4 && void 0 !== arguments[4] ? arguments[4] : 1;
                        a && (e.strokeStyle = a), i && (e.lineWidth = i), e.beginPath(), e.moveTo(t[0], t[1]), e.lineTo(n[0], n[1]), e.stroke()
                    }
                    return Object(Qe.jsxs)(Qe.Fragment, {
                        children: [Object(Qe.jsxs)("div", {
                            className: Yn.a.canvasCcontainer,
                            children: [o ? "Screen Normal" : "AOD", " (", s.width, " x ", s.height, ")", Object(Qe.jsxs)("div", {
                                children: ["x: ", c, ", y: ", b]
                            }), Object(Qe.jsx)(Ln, {
                                id: "canvasPreview",
                                draw: function(e, a) {
                                    t && n && (e ? (a.clearRect(0, 0, e.width, e.height), o ? function(e, t, a) {
                                        n.background && function(e, t, n, a) {
                                            var i, o, s, r;
                                            if (a.color && j.GFG_Fun(a.color) && (t.fillStyle = a.color, t.fillRect(0, 0, e.width, e.height)), (null === a || void 0 === a || null === (i = a.image) || void 0 === i || null === (o = i.json) || void 0 === o ? void 0 : o.ImageIndex) >= 0) {
                                                var l = jn(a.image.json.ImageIndex, n);
                                                l && t.drawImage(l, a.image.json.X, a.image.json.Y)
                                            }
                                            if (null === a || void 0 === a || null === (s = a.floatingLayer) || void 0 === s || null === (r = s.json) || void 0 === r ? void 0 : r.ImageIndex) {
                                                var d, c, u, m = jn(null === (d = a.floatingLayer) || void 0 === d ? void 0 : d.json.ImageIndex, n);
                                                m && t.drawImage(m, null === (c = a.floatingLayer) || void 0 === c ? void 0 : c.json.X, null === (u = a.floatingLayer) || void 0 === u ? void 0 : u.json.Y)
                                            }
                                        }(e, t, a, n.background);
                                        n.date && function(e, t, n, a, i) {
                                            if (n.oneLineYear) {
                                                if (n.year.enabled) {
                                                    var o = [a.year.toString(), n.year.paddingZero ? a.month.toString().padStart(2, "0") : a.month.toString(), n.year.paddingZero ? a.day.toString().padStart(2, "0") : a.day.toString()];
                                                    fn(e, t, n.year, o, n.oneLineDelimiter, i)
                                                }
                                            } else if (n.oneLineMonth) {
                                                if (n.month.enabled) {
                                                    var s = [n.month.paddingZero ? a.month.toString().padStart(2, "0") : a.month.toString(), n.month.paddingZero ? a.day.toString().padStart(2, "0") : a.day.toString()];
                                                    fn(e, t, n.month, s, n.oneLineDelimiter, i)
                                                }
                                            } else {
                                                if (n.year.enabled)
                                                    if (n.month.enabled && n.month.follow) {
                                                        var r = [{
                                                            snumber: a.year.toString(),
                                                            suffix: n.year.delimiter,
                                                            dataType: n.year.dataType
                                                        }, {
                                                            snumber: n.month.paddingZero ? a.month.toString().padStart(2, "0") : a.month.toString(),
                                                            suffix: n.month.delimiter,
                                                            dataType: n.month.dataType
                                                        }];
                                                        n.day.enabled && n.day.follow && r.push({
                                                            snumber: n.day.paddingZero ? a.day.toString().padStart(2, "0") : a.day.toString(),
                                                            suffix: n.day.delimiter,
                                                            dataType: n.day.dataType
                                                        }), vn(e, t, n.year, r, i)
                                                    } else if (xn(e, t, n.year, a.year, null, i, !0, null, null, null, n.year.dataType), n.year.delimiter && n.year.delimiterCoords) {
                                                    var l = jn(n.year.delimiter, t);
                                                    l && e.drawImage(l, n.year.delimiterCoords.X, n.year.delimiterCoords.Y)
                                                }
                                                if (n.month.enabled && !n.month.follow)
                                                    if (n.day.enabled && n.day.follow) {
                                                        var d = [{
                                                            snumber: n.month.paddingZero ? a.month.toString().padStart(2, "0") : a.month.toString(),
                                                            suffix: n.month.dataType,
                                                            dataType: n.month.dataType
                                                        }, {
                                                            snumber: n.day.paddingZero ? a.day.toString().padStart(2, "0") : a.day.toString(),
                                                            suffix: n.day.dataType,
                                                            dataType: n.day.dataType
                                                        }];
                                                        vn(e, t, n.month, d, i)
                                                    } else if (xn(e, t, n.month, a.month, null, i, !1, null, null, null, n.month.dataType), n.month.delimiter && n.month.delimiterCoords) {
                                                    var c = jn(n.month.delimiter, t);
                                                    c && e.drawImage(c, n.month.delimiterCoords.X, n.month.delimiterCoords.Y)
                                                }
                                                if (n.day.enabled && !n.day.follow && (xn(e, t, n.day, a.day, null, i, !0, null, null, null, n.day.dataType), n.day.delimiter && n.day.delimiterCoords)) {
                                                    var u = jn(n.day.delimiter, t);
                                                    u && e.drawImage(u, n.day.delimiterCoords.X, n.day.delimiterCoords.Y)
                                                }
                                            }
                                            if (n.monthAsWord.enabled && Cn(e, t, n.monthAsWord.json, a.month - 1, 12), n.weekday.enabled && Cn(e, t, n.weekday.json, a.weekday, 7), n.weekdayProgress.iconSetProgress.enabled && In(e, t, n.weekdayProgress.iconSetProgress.json, a.weekday, 7), n.ampm.enabled)
                                                if (a.hours < 12) {
                                                    var m = jn(n.ampm.json.AmImageIndexEN, t);
                                                    if (m) {
                                                        var h = n.ampm.json.CommonX ? n.ampm.json.CommonX : n.ampm.json.CoordinatesAM ? n.ampm.json.CoordinatesAM.X : 0,
                                                            g = n.ampm.json.CommonY ? n.ampm.json.CommonY : n.ampm.json.CoordinatesAM ? n.ampm.json.CoordinatesAM.Y : 0;
                                                        e.drawImage(m, h, g)
                                                    }
                                                } else {
                                                    var b = jn(n.ampm.json.PmImageIndexEN, t);
                                                    if (b) {
                                                        var j = n.ampm.json.CommonX ? n.ampm.json.CommonX : n.ampm.json.CoordinatesPM ? n.ampm.json.CoordinatesPM.X : 0,
                                                            p = n.ampm.json.CommonY ? n.ampm.json.CommonY : n.ampm.json.CoordinatesPM ? n.ampm.json.CoordinatesPM.Y : 0;
                                                        e.drawImage(b, j, p)
                                                    }
                                                }
                                        }(t, a, n.date, i, N);
                                        n.status && function(e, t, n, a) {
                                            n.bluetooth.enabled && Tn(e, t, n.bluetooth.json, a.bluetooth), n.doNotDisturb.enabled && Tn(e, t, n.doNotDisturb.json, a.dnd), n.alarm.enabled && Tn(e, t, n.alarm.json, a.alarm), n.lock.enabled && Tn(e, t, n.lock.json, a.lock)
                                        }(t, a, n.status, i);
                                        n.battery && function(e, t, n, a, i, o) {
                                            if (n) {
                                                if (n.text.enabled && xn(e, t, n.text.imageNumber, a.battery, null, i, !1, null, n.text.prefix, null, n.text.suffix), n.icon.enabled && n.icon.json.ImageIndex) {
                                                    var s = jn(n.icon.json.ImageIndex, t);
                                                    s && e.drawImage(s, n.icon.json.X, n.icon.json.Y)
                                                }
                                                n.imageProgress.enabled && Cn(e, t, n.imageProgress.json, a.battery, a.batteryGoal), n.iconSetProgress.enabled && In(e, t, n.iconSetProgress.json, a.battery, a.batteryGoal), n.scale.enabled && (n.scale.bottomImage.enabled && wn(e, t, n.scale.bottomImage.json), Sn(e, t, n.scale.pointerScaleJson, a.battery, a.batteryGoal))
                                            }
                                        }(t, a, n.battery, i, N);
                                        n.weather && function(e, t, n, a, i, o, s) {
                                            if (n) {
                                                if (n.current.watchNumber.enabled && xn(e, t, n.current.watchNumber, i.temperature, null, o, !1, n.current.minus, null, null, n.current.suffix), n.lowest.watchNumber.enabled && xn(e, t, n.lowest.watchNumber, i.temperatureMin, null, o, !1, n.lowest.minus, null, null, n.lowest.suffix), n.highest.watchNumber.enabled && xn(e, t, n.highest.watchNumber, i.temperatureMax, null, o, !1, n.highest.minus, null, null, n.highest.suffix), n.icon.enabled && Cn(e, t, n.icon.json, i.weatherIcon, 26), n.oneLineMinMax.enabled) {
                                                    var r = i.temperatureMin,
                                                        l = i.temperatureMax,
                                                        d = [n.oneLineMinMax.paddingZero ? r < 0 ? "-" + Math.abs(r).toString().padStart(2, "0") : r.toString().padStart(2, "0") : r.toString(), n.oneLineMinMax.paddingZero ? l < 0 ? "-" + Math.abs(l).toString().padStart(2, "0") : l.toString().padStart(2, "0") : l.toString()];
                                                    fn(e, t, n.oneLineMinMax, d, n.oneLineDelimiter, o, n.oneLineDegrees, null, n.oneLineMinus)
                                                }
                                                a.humidityIcon.enabled && wn(e, t, a.humidityIcon.json), a.humidityNumber.enabled && xn(e, t, a.humidityNumber, i.humidity, null, o, !1, null, null, null, a.humiditySuffix), a.humidityProgress.imageProgress.enabled && Cn(e, t, a.humidityProgress.imageProgress.json, i.humidity, i.humidityGoal), a.airQualityIcon.enabled && wn(e, t, a.airQualityIcon.json), a.airQualityNumber.enabled && xn(e, t, a.airQualityNumber, i.airQuality, null, o, !1, null, null, null, null), a.uvIcon.enabled && wn(e, t, a.uvIcon.json), a.uvNumber.enabled && xn(e, t, a.uvNumber, i.uvIndex, null, o, !1, null, null, null, a.uvSuffixImageIndex), a.uvProgress.imageProgress.enabled && Cn(e, t, a.uvProgress.imageProgress.json, i.uvIndex, i.uvIndexGoal), a.uvShortcut.enabled && Dn(e, a.uvShortcut.json, s)
                                            }
                                        }(t, a, n.weather, n.weatherext, i, N, k);
                                        n.activity && function(e, t, n, a, i, o) {
                                            Nn(e, t, n.activity.steps, a.steps, a.stepsGoal, i, o), Nn(e, t, n.activity.calories, a.calories, a.caloriesGoal, i, o), Nn(e, t, n.activity.distance, a.distance, null, i, o), Nn(e, t, n.activity.heartRate, a.hearthrate, a.hearthrateGoal, i, o), Nn(e, t, n.activity.pai, a.pai, a.paiGoal, i, o), Nn(e, t, n.activity.standUp, a.standup, a.standupGoal, i, o)
                                        }(t, a, n, i, N, k);
                                        n.activity.caloriesSeparatedDigits.enabled && function(e, t, n, a, i) {
                                            if (n.Ones) {
                                                var o = Math.floor(a / 1e3);
                                                (a >= 1e3 || i) && Cn(e, t, n.Ones, o, 10)
                                            }
                                            if (n.Tens) {
                                                var s = Math.floor(a % 1e3 / 100);
                                                (a >= 100 || i) && Cn(e, t, n.Tens, s, 10)
                                            }
                                            if (n.Hundreds) {
                                                var r = Math.floor(a % 1e3 % 100 / 10);
                                                (a >= 10 || i) && Cn(e, t, n.Hundreds, r, 10)
                                            }
                                            n.Thousands && Cn(e, t, n.Thousands, a % 1e3 % 100 % 10, 10)
                                        }(t, a, n.activity.caloriesSeparatedDigits.json, i.calories, !1);
                                        n.activity.stepsSeparatedDigits.enabled && function(e, t, n, a, i) {
                                            if (n.Ones) {
                                                var o = Math.floor(a / 1e4);
                                                (a >= 1e4 || i) && Cn(e, t, n.Ones, o, 10)
                                            }
                                            if (n.Tens) {
                                                var s = Math.floor(a % 1e4 / 1e3);
                                                (a >= 1e3 || i) && Cn(e, t, n.Tens, s, 10)
                                            }
                                            if (n.Hundreds) {
                                                var r = Math.floor(a % 1e4 % 1e3 / 100);
                                                (a >= 100 || i) && Cn(e, t, n.Hundreds, r, 10)
                                            }
                                            if (n.Thousands) {
                                                var l = Math.floor(a % 1e4 % 1e3 % 100 / 10);
                                                (a >= 10 || i) && Cn(e, t, n.Thousands, l, 10)
                                            }
                                            n.TenThousands && Cn(e, t, n.TenThousands, a % 1e4 % 1e3 % 100 % 10, 10)
                                        }(t, a, n.activity.stepsSeparatedDigits.json, i.steps, !1);
                                        n.activity.batterySeparatedDigits.enabled && Pn(t, a, n.activity.batterySeparatedDigits.json, i.battery, !1);
                                        n.activity.heartRateSeparatedDigits.enabled && Pn(t, a, n.activity.heartRateSeparatedDigits.json, i.hearthrate, !1);
                                        n.time && (function(e, t, n, a, i, o) {
                                            if (n.alarmTime.hours.enabled)
                                                if (n.alarmTime.minutes.enabled && n.alarmTime.minutes.follow) {
                                                    var s = [{
                                                        snumber: n.alarmTime.hours.paddingZero ? a.alarmHours.toString().padStart(2, "0") : a.alarmHours.toString(),
                                                        suffix: n.alarmTime.hours.delimiter,
                                                        dataType: n.alarmTime.hours.dataType
                                                    }, {
                                                        snumber: n.alarmTime.minutes.paddingZero ? a.alarmMinutes.toString().padStart(2, "0") : a.alarmMinutes.toString(),
                                                        suffix: n.alarmTime.minutes.delimiter,
                                                        dataType: n.alarmTime.minutes.dataType
                                                    }];
                                                    vn(e, t, n.alarmTime.hours, s, i)
                                                } else if (xn(e, t, n.alarmTime.hours, a.alarmHours, null, i, !1, null, null, null, n.alarmTime.hours.delimiter), n.alarmTime.hours.dataType && n.alarmTime.hours.delimiterCoords) {
                                                var r = jn(n.alarmTime.hours.dataType, t);
                                                r && e.drawImage(r, n.alarmTime.hours.delimiterCoords.X, n.alarmTime.hours.delimiterCoords.Y)
                                            }
                                            if (n.alarmTime.minutes.enabled && !n.alarmTime.minutes.follow && (xn(e, t, n.alarmTime.minutes, a.alarmMinutes, null, i, !1, null, null, null, n.alarmTime.minutes.delimiter), n.alarmTime.minutes.dataType && n.alarmTime.minutes.delimiterCoords)) {
                                                var l = jn(n.alarmTime.minutes.dataType, t);
                                                l && e.drawImage(l, n.alarmTime.minutes.delimiterCoords.X, n.alarmTime.minutes.delimiterCoords.Y)
                                            }
                                            console.log(a.alarmEnabled, n.alarmImage.enabled, n.noAlarm.enabled), a.alarmEnabled ? n.alarmImage.enabled && wn(e, t, n.alarmImage.json) : n.noAlarm.enabled && wn(e, t, n.noAlarm.json), n.shortcut.enabled && Dn(e, n.shortcut.json, o)
                                        }(t, a, n.time.alarm, i, N, k), function(e, t, n, a, i, o) {
                                            if (n.sunsetOneLine.enabled) {
                                                var s = [a.sunsetHours.toString().padStart(2, "0"), a.sunsetMinutes.toString().padStart(2, "0")];
                                                fn(e, t, n.sunsetOneLine, s, n.sunsetOneLine.delimiter, i, null, n.sunsetOneLine.prefix, null)
                                            }
                                            if (n.sunriseOneLine.enabled) {
                                                var r = [a.sunriseHours.toString().padStart(2, "0"), a.sunriseMinutes.toString().padStart(2, "0")];
                                                fn(e, t, n.sunriseOneLine, r, n.sunriseOneLine.delimiter, i, null, n.sunriseOneLine.prefix, null)
                                            }
                                            n.sunsetIcon.enabled && wn(e, t, n.sunsetIcon.json), n.sunriseIcon.enabled && wn(e, t, n.sunriseIcon.json), n.sunsetShortcut.enabled && Dn(e, n.sunsetShortcut.json, o), n.sunriseShortcut.enabled && Dn(e, n.sunriseShortcut.json, o)
                                        }(t, a, n.time.sunset, i, N, k), function(e, t, n, a, i) {
                                            if (n.timeDigitalCommon.hours.enabled)
                                                if (n.timeDigitalCommon.minutes.enabled && n.timeDigitalCommon.minutes.follow) {
                                                    var o = [{
                                                        snumber: n.timeDigitalCommon.hours.paddingZero ? a.hours.toString().padStart(2, "0") : a.hours.toString(),
                                                        suffix: n.timeDigitalCommon.hours.delimiter,
                                                        dataType: n.timeDigitalCommon.hours.dataType
                                                    }, {
                                                        snumber: n.timeDigitalCommon.minutes.paddingZero ? a.minutes.toString().padStart(2, "0") : a.minutes.toString(),
                                                        suffix: n.timeDigitalCommon.minutes.delimiter,
                                                        dataType: n.timeDigitalCommon.minutes.dataType
                                                    }];
                                                    n.timeDigitalCommon.seconds.enabled && n.timeDigitalCommon.seconds.follow && o.push({
                                                        snumber: n.timeDigitalCommon.seconds.paddingZero ? a.seconds.toString().padStart(2, "0") : a.seconds.toString(),
                                                        suffix: n.timeDigitalCommon.seconds.delimiter,
                                                        dataType: n.timeDigitalCommon.seconds.dataType
                                                    }), vn(e, t, n.timeDigitalCommon.hours, o, i)
                                                } else if (xn(e, t, n.timeDigitalCommon.hours, a.hours, null, i, !1, null, null, null, n.timeDigitalCommon.hours.delimiter), n.timeDigitalCommon.hours.dataType && n.timeDigitalCommon.hours.delimiterCoords) {
                                                var s = jn(n.timeDigitalCommon.hours.dataType, t);
                                                s && e.drawImage(s, n.timeDigitalCommon.hours.delimiterCoords.X, n.timeDigitalCommon.hours.delimiterCoords.Y)
                                            }
                                            if (n.timeDigitalCommon.minutes.enabled && !n.timeDigitalCommon.minutes.follow)
                                                if (n.timeDigitalCommon.seconds.enabled && n.timeDigitalCommon.seconds.follow) {
                                                    var r = [{
                                                        snumber: n.timeDigitalCommon.minutes.paddingZero ? a.minutes.toString().padStart(2, "0") : a.minutes.toString(),
                                                        suffix: n.timeDigitalCommon.minutes.delimiter,
                                                        dataType: n.timeDigitalCommon.minutes.dataType
                                                    }, {
                                                        snumber: n.timeDigitalCommon.seconds.paddingZero ? a.seconds.toString().padStart(2, "0") : a.seconds.toString(),
                                                        suffix: n.timeDigitalCommon.seconds.delimiter,
                                                        dataType: n.timeDigitalCommon.seconds.dataType
                                                    }];
                                                    vn(e, t, n.timeDigitalCommon.minutes, r, i)
                                                } else if (xn(e, t, n.timeDigitalCommon.minutes, a.minutes, null, i, !1, null, null, null, n.timeDigitalCommon.minutes.delimiter), n.timeDigitalCommon.minutes.dataType && n.timeDigitalCommon.minutes.delimiterCoords) {
                                                var l = jn(n.timeDigitalCommon.minutes.dataType, t);
                                                l && e.drawImage(l, n.timeDigitalCommon.minutes.delimiterCoords.X, n.timeDigitalCommon.minutes.delimiterCoords.Y)
                                            }
                                            if (n.timeDigitalCommon.seconds.enabled && !n.timeDigitalCommon.seconds.follow && (xn(e, t, n.timeDigitalCommon.seconds, a.seconds, null, i, !1, null, null, null, n.timeDigitalCommon.seconds.delimiter), n.timeDigitalCommon.seconds.dataType && n.timeDigitalCommon.seconds.delimiterCoords)) {
                                                var d = jn(n.timeDigitalCommon.seconds.dataType, t);
                                                d && e.drawImage(d, n.timeDigitalCommon.seconds.delimiterCoords.X, n.timeDigitalCommon.seconds.delimiterCoords.Y)
                                            }
                                            var c, u;
                                            n.timeDigitalSeparated.hours.enabled && (Mn(e, t, n.timeDigitalSeparated.hours.json, a.hours, n.timeDigitalSeparated.paddingZeroHours), (null === (c = n.timeDigitalSeparated.separatorHours) || void 0 === c ? void 0 : c.enabled) && wn(e, t, n.timeDigitalSeparated.separatorHours.json)), n.timeDigitalSeparated.minutes.enabled && (Mn(e, t, n.timeDigitalSeparated.minutes.json, a.minutes, n.timeDigitalSeparated.paddingZeroMinutes), (null === (u = n.timeDigitalSeparated.separatorMinutes) || void 0 === u ? void 0 : u.enabled) && wn(e, t, n.timeDigitalSeparated.separatorMinutes.json)), n.timeDigitalSeparated.seconds.enabled && Mn(e, t, n.timeDigitalSeparated.seconds.json, a.seconds, !0)
                                        }(t, a, n.time, i, N), function(e, t, n, a, i, o) {
                                            var s, r, l;
                                            (null === (s = n.timeAnalog.hours) || void 0 === s ? void 0 : s.enabled) && (a.hours < 12 ? kn(e, t, n.timeAnalog.hours, a.hours, 12, n.timeAnalog.commonCenterCoordinates, i, o) : kn(e, t, n.timeAnalog.hours, a.hours - 12, 12, n.timeAnalog.commonCenterCoordinates, i, o)), (null === (r = n.timeAnalog.minutes) || void 0 === r ? void 0 : r.enabled) && kn(e, t, n.timeAnalog.minutes, a.minutes, 60, n.timeAnalog.commonCenterCoordinates, i, o), (null === (l = n.timeAnalog.seconds) || void 0 === l ? void 0 : l.enabled) && kn(e, t, n.timeAnalog.seconds, a.seconds, 60, n.timeAnalog.commonCenterCoordinates, i, o)
                                        }(t, a, n.time, i, s.width, s.height));
                                        n.animation.imageSetAnimation && n.animation.imageSetAnimation.forEach((function(e, n) {
                                            Cn(t, a, e.ImageProgress, i.animation[n], e.ImageProgress.ImagesCount)
                                        }));
                                        n.shortcuts.json && n.shortcuts.json.forEach((function(e) {
                                            wn(t, a, e.Icon), Dn(t, e.Element, k)
                                        }))
                                    }(e, a, t) : function(e, t, a) {
                                        n.aod && function(e, t) {
                                            t.fillStyle = "black", t.fillRect(0, 0, e.width, e.height)
                                        }(e, t);
                                        n.aod.date && function(e, t, n, a, i, o, s) {
                                            if (a.monthAndDay.enabled) {
                                                if (a.monthAndDay.enabled) {
                                                    var r = [a.monthAndDay.paddingZero ? o.month.toString().padStart(2, "0") : o.month.toString(), a.monthAndDay.paddingZero ? o.day.toString().padStart(2, "0") : o.day.toString()];
                                                    fn(e, t, a.monthAndDay, r, a.separatorImageIndex, s)
                                                }
                                            } else {
                                                if (n.month.enabled)
                                                    if (n.day.enabled && n.day.follow) {
                                                        var l = [{
                                                            snumber: n.month.paddingZero ? o.month.toString().padStart(2, "0") : o.month.toString(),
                                                            suffix: n.month.dataType
                                                        }, {
                                                            snumber: n.day.paddingZero ? o.day.toString().padStart(2, "0") : o.day.toString(),
                                                            suffix: n.day.dataType
                                                        }];
                                                        vn(e, t, n.month, l, s)
                                                    } else xn(e, t, n.month, o.month, null, s, !1, null, null, null, n.month.dataType);
                                                if (n.day.enabled && !n.day.follow && xn(e, t, n.day, o.day, null, s, !0, null, null, null, n.day.dataType), n.day.enabled && n.day.delimiter && n.day.delimiterCoords) {
                                                    var d = jn(n.day.dataType, t);
                                                    d && e.drawImage(d, n.day.delimiterCoords.X, n.day.delimiterCoords.Y)
                                                }
                                                if (n.month.enabled && n.month.delimiter && n.month.delimiterCoords) {
                                                    var c = jn(n.month.dataType, t);
                                                    c && e.drawImage(c, n.month.delimiterCoords.X, n.month.delimiterCoords.Y)
                                                }
                                            }
                                            i.enabled && Cn(e, t, i.json, o.weekday, 7)
                                        }(t, a, n.aod.date, n.aod.dateOneLine, n.aod.weekday, i, N);
                                        n.aod.steps && Nn(t, a, n.aod.steps, i.steps, i.stepsGoal, N, k);
                                        n.aod.time && (function(e, t, n, a, i) {
                                            if (n.timeDigital.hours.enabled)
                                                if (n.timeDigital.minutes.enabled && n.timeDigital.minutes.follow) {
                                                    var o = [{
                                                        snumber: n.timeDigital.hours.paddingZero ? a.hours.toString().padStart(2, "0") : a.hours.toString(),
                                                        suffix: n.timeDigital.hours.delimiter,
                                                        dataType: n.timeDigital.hours.dataType
                                                    }, {
                                                        snumber: n.timeDigital.minutes.paddingZero ? a.minutes.toString().padStart(2, "0") : a.minutes.toString(),
                                                        suffix: n.timeDigital.minutes.delimiter,
                                                        dataType: n.timeDigital.minutes.dataType
                                                    }];
                                                    vn(e, t, n.timeDigital.hours, o, i)
                                                } else xn(e, t, n.timeDigital.hours, a.hours, null, i, !1, null, null, null, null);
                                            var s;
                                            if (n.timeDigital.minutes.enabled && !n.timeDigital.minutes.follow && xn(e, t, n.timeDigital.minutes, a.minutes, null, i, !1, null, null, null, null), n.timeSeparateDigits.hours.enabled && (Mn(e, t, n.timeSeparateDigits.hours.json, a.hours, n.timeSeparateDigits.paddingZero), (null === (s = n.timeSeparateDigits.separator) || void 0 === s ? void 0 : s.enabled) && wn(e, t, n.timeSeparateDigits.separator.json)), n.timeSeparateDigits.minutes.enabled && Mn(e, t, n.timeSeparateDigits.minutes.json, a.minutes, n.timeSeparateDigits.paddingZero), n.amPm.enabled)
                                                if (a.hours < 12) {
                                                    var r = jn(n.amPm.json.AmImageIndexEN, t);
                                                    if (r) {
                                                        var l = n.amPm.json.CommonX ? n.amPm.json.CommonX : n.amPm.json.CoordinatesAM ? n.amPm.json.CoordinatesAM.X : 0,
                                                            d = n.amPm.json.CommonY ? n.amPm.json.CommonY : n.amPm.json.CoordinatesAM ? n.amPm.json.CoordinatesAM.Y : 0;
                                                        e.drawImage(r, l, d)
                                                    }
                                                } else {
                                                    var c = jn(n.amPm.json.PmImageIndexEN, t);
                                                    if (c) {
                                                        var u = n.amPm.json.CommonX ? n.amPm.json.CommonX : n.amPm.json.CoordinatesPM ? n.amPm.json.CoordinatesPM.X : 0,
                                                            m = n.amPm.json.CommonY ? n.amPm.json.CommonY : n.amPm.json.CoordinatesPM ? n.amPm.json.CoordinatesPM.Y : 0;
                                                        e.drawImage(c, u, m)
                                                    }
                                                }
                                        }(t, a, n.aod.time, i, N), function(e, t, n, a, i, o) {
                                            var s, r;
                                            (null === (s = n.hours) || void 0 === s ? void 0 : s.enabled) && (a.hours < 12 ? kn(e, t, n.hours, a.hours, 12, n.commonCenterCoordinates, i, o) : kn(e, t, n.hours, a.hours - 12, 12, n.commonCenterCoordinates, i, o)), (null === (r = n.minutes) || void 0 === r ? void 0 : r.enabled) && kn(e, t, n.minutes, a.minutes, 60, n.commonCenterCoordinates, i, o)
                                        }(t, a, n.aod.time.timeAnalog, i, s.width, s.height))
                                    }(e, a, t), function(e) {
                                        if (!x && !w) return;
                                        for (var t = x ? "white" : "black", n = 20, a = s.width / 2; a > 0; a -= n) L(e, [a, 0], [a, s.height], t, 1);
                                        for (var i = s.width / 2; i < s.width; i += n) L(e, [i, 0], [i, s.height], t, 1);
                                        for (var o = s.height / 2; o > 0; o -= n) L(e, [0, o], [s.width, o], t, 1);
                                        for (var r = s.height / 2; r < s.height; r += n) L(e, [0, r], [s.width, r], t, 1);
                                        L(e, [s.width / 2 - 1, 0], [s.width / 2 - 1, s.height], t, 2), L(e, [0, s.height / 2 - 1], [s.width, s.height / 2 - 1], t, 2)
                                    }(a)) : console.error("don't find canvas with id canvasPreview"))
                                },
                                className: Yn.a.canvasPreview,
                                width: s.width,
                                height: s.height,
                                onClick: function(e) {
                                    var t = document.getElementById("canvasPreview").getBoundingClientRect(),
                                        n = e.clientX - t.left,
                                        a = e.clientY - t.top;
                                    n = Math.min(s.width, Math.max(0, Math.round(n))), a = Math.min(s.height, Math.max(0, Math.round(a))), u(n), p(a)
                                }
                            })]
                        }), Object(Qe.jsx)("div", {
                            className: "container d-flex justify-content-center",
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                style: {
                                    width: "max-content"
                                },
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    id: "addon-wrapping",
                                    children: "White grid"
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: x,
                                        onChange: function() {
                                            var e = !x;
                                            O(e), localStorage.setItem(Hn, JSON.stringify(e))
                                        }
                                    })
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    id: "addon-wrapping",
                                    children: "Black grid"
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: w,
                                        onChange: function() {
                                            var e = !w;
                                            C(e), localStorage.setItem(Hn, JSON.stringify(e))
                                        }
                                    })
                                })]
                            })
                        }), Object(Qe.jsx)("div", {
                            className: "container d-flex justify-content-center",
                            children: Object(Qe.jsxs)("div", {
                                className: "input-group input-group-sm",
                                style: {
                                    width: "max-content"
                                },
                                children: [Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    id: "addon-wrapping",
                                    children: "border on digit"
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: N,
                                        onChange: function() {
                                            var e = !N;
                                            M(e), localStorage.setItem(Bn, JSON.stringify(e))
                                        }
                                    })
                                }), Object(Qe.jsx)("span", {
                                    className: "input-group-text",
                                    id: "addon-wrapping",
                                    children: "border on shortcut"
                                }), Object(Qe.jsx)("div", {
                                    className: "input-group-text",
                                    children: Object(Qe.jsx)("input", {
                                        className: "form-check-input mt-0",
                                        type: "checkbox",
                                        checked: k,
                                        onChange: function() {
                                            var e = !k;
                                            A(e), localStorage.setItem(Xn, JSON.stringify(e))
                                        }
                                    })
                                })]
                            })
                        })]
                    })
                };
            var Fn = function() {
                var e = Object(a.useContext)(m),
                    t = e.device,
                    n = e.setDevice;

                function i(e) {
                    localStorage.setItem(Je.DEVICE_KEY, JSON.stringify(e)), n(e)
                }
                return Object(Qe.jsxs)(ze.a, {
                    className: "mt-3",
                    children: [Object(Qe.jsx)(ze.a.Header, {
                        children: "Device"
                    }), Object(Qe.jsxs)(ze.a.Body, {
                        children: [Object(Qe.jsxs)("div", {
                            className: "form-check",
                            children: [Object(Qe.jsx)("input", {
                                className: "form-check-input",
                                type: "radio",
                                name: "device",
                                id: "device_gts2mini",
                                value: "gts2mini",
                                checked: t.deviceId === Je.devices.gts2minie.deviceId,
                                onChange: function() {
                                    return i(Je.devices.gts2minie)
                                }
                            }), Object(Qe.jsx)("label", {
                                className: "form-check-label",
                                children: Je.devices.gts2minie.title
                            })]
                        }), Object(Qe.jsxs)("div", {
                            className: "form-check",
                            children: [Object(Qe.jsx)("input", {
                                className: "form-check-input",
                                type: "radio",
                                name: "device",
                                id: "device_bipu",
                                value: "bipu",
                                checked: t.deviceId === Je.devices.bipu.deviceId,
                                onChange: function() {
                                    return i(Je.devices.bipu)
                                }
                            }), Object(Qe.jsx)("label", {
                                className: "form-check-label",
                                children: Je.devices.bipu.title
                            })]
                        }), Object(Qe.jsxs)("div", {
                            className: "form-check",
                            children: [Object(Qe.jsx)("input", {
                                className: "form-check-input",
                                type: "radio",
                                name: "device",
                                id: "device_bip3",
                                value: "bip3",
                                checked: t.deviceId === Je.devices.bip3.deviceId,
                                onChange: function() {
                                    return i(Je.devices.bip3)
                                }
                            }), Object(Qe.jsx)("label", {
                                className: "form-check-label",
                                children: Je.devices.bip3.title
                            })]
                        })]
                    })]
                })
            };
            var Wn = function() {
                    var e = Object(a.useContext)(m).images;
                    return Object(Qe.jsx)("div", {
                        className: "container d-flex justify-content-center",
                        children: e.length > 0 ? Object(Qe.jsxs)("div", {
                            children: [Object(Qe.jsxs)("h2", {
                                children: ["number of images: ", e.length, " "]
                            }), Object(Qe.jsx)("ul", {
                                className: "list-group blocks",
                                style: {
                                    width: "100%"
                                },
                                children: e.map((function(e) {
                                    return Object(Qe.jsxs)("li", {
                                        value: e.id,
                                        className: "list-group-item fileitem",
                                        children: [Object(Qe.jsx)("img", {
                                            src: e.image.src,
                                            alt: e.name,
                                            width: 30
                                        }), e.name]
                                    }, e.id)
                                }))
                            })]
                        }) : Object(Qe.jsx)("div", {
                            children: "no uploaded images"
                        })
                    })
                },
                Zn = [{
                    id: 0,
                    name: "Preview",
                    el: Object(Qe.jsx)(Rn, {})
                }, {
                    id: 1,
                    name: "Uploaded Images",
                    el: Object(Qe.jsx)(Wn, {})
                }, {
                    id: 2,
                    name: "Json",
                    el: Object(Qe.jsx)(qt, {})
                }, {
                    id: 3,
                    name: "Settings",
                    el: Object(Qe.jsx)(Fn, {})
                }],
                Gn = function() {
                    var e = Object(a.useState)(0),
                        t = Object(r.a)(e, 2),
                        n = t[0],
                        i = t[1];
                    return Object(Qe.jsxs)("div", {
                        children: [Object(Qe.jsxs)("ul", {
                            className: "nav nav-tabs",
                            children: [Zn.map((function(e) {
                                return Object(Qe.jsx)("li", {
                                    className: "nav-item",
                                    children: Object(Qe.jsx)("button", {
                                        className: "nav-link ".concat(n === e.id ? "active" : "", " "),
                                        onClick: function() {
                                            return i(e.id)
                                        },
                                        children: e.name
                                    })
                                }, e.id)
                            })), Object(Qe.jsxs)("li", {
                                className: "navbar-text",
                                style: {
                                    marginRight: 0,
                                    marginLeft: "auto"
                                },
                                children: ["v. ", Je.version]
                            })]
                        }), Zn[n].el]
                    })
                },
                Jn = function e() {
                    Object(h.a)(this, e), this._date = new Date, this.year = this._date.getFullYear(), this.month = this._date.getMonth() + 1, this.monthasword = this._date.getMonth(), this.day = this._date.getDate(), this.hours = this._date.getHours(), this.minutes = this._date.getMinutes(), this.alarmEnabled = !0, this.alarmHours = this._date.getHours(), this.alarmMinutes = this._date.getMinutes(), this.sunsetHours = 17, this.sunsetMinutes = 42, this.sunriseHours = 5, this.sunriseMinutes = 38, this.seconds = this._date.getSeconds(), this.weekday = this._date.getDay() > 0 ? this._date.getDay() - 1 : 6, this.batteryGoal = 100, this.battery = Math.round(Math.random() * this.batteryGoal), this.stepsGoal = 1e3 * (Math.round(5 * Math.random()) + 5), this.steps = Math.round(Math.random() * this.stepsGoal), this.caloriesGoal = 200, this.calories = Math.round(Math.random() * this.caloriesGoal), this.hearthrateGoal = 220, this.hearthrate = Math.round(200 * Math.random()), this.distance = Math.round(1e3 * Math.random()) + 1e3, this.paiGoal = 100, this.pai = Math.round(Math.random() * this.paiGoal), this.standupGoal = 12, this.standup = Math.round(Math.random() * this.standupGoal), this.bluetooth = !0, this.dnd = !0, this.lock = !1, this.alarm = !0, this.temperature = Math.round(10 * Math.random()), this.temperatureMin = this.temperature - Math.round(10 * Math.random()), this.temperatureMax = this.temperature + Math.round(10 * Math.random()), this.weatherIcon = Math.round(29 * Math.random()), this.uvIndexGoal = 11, this.uvIndex = Math.round(Math.random() * this.uvIndexGoal), this.airQualityGoal = 500, this.airQuality = Math.round(Math.random() * this.airQualityGoal), this.humidityGoal = 100, this.humidity = Math.round(Math.random() * this.humidityGoal), this.windForce = Math.round(12 * Math.random()), this.airPressureGoal = 100, this.airPressure = Math.round(Math.random() * this.airPressureGoal), this.stressGoal = 100, this.stress = Math.round(Math.random() * this.stressGoal), this.fatBurningGoal = 30, this.fatBurning = Math.round(Math.random() * this.fatBurningGoal), this.animation = []
                },
                _n = function() {
                    var e = Object(a.useState)([]),
                        t = Object(r.a)(e, 2),
                        n = t[0],
                        i = t[1],
                        o = Object(a.useState)(new Ge),
                        s = Object(r.a)(o, 2),
                        u = s[0],
                        h = s[1],
                        g = Object(a.useState)(new Jn),
                        b = Object(r.a)(g, 2),
                        j = b[0],
                        p = b[1],
                        v = Object(a.useState)(null),
                        f = Object(r.a)(v, 2),
                        x = f[0],
                        O = f[1],
                        y = Object(a.useState)(!0),
                        I = Object(r.a)(y, 2),
                        w = I[0],
                        C = I[1],
                        S = Object(a.useState)(Je.devices.gts2minie),
                        D = Object(r.a)(S, 2),
                        N = D[0],
                        M = D[1];
                    return Object(a.useEffect)((function() {
                        M(function() {
                            var e = JSON.parse(localStorage.getItem(Je.DEVICE_KEY));
                            return e || (e = Je.devices.gts2minie), e
                        }())
                    }), []), Object(Qe.jsx)(m.Provider, {
                        value: {
                            images: n,
                            setImages: i,
                            watchface: u,
                            setWatchface: h,
                            watchState: j,
                            setWatchState: p,
                            jsonName: x,
                            setJsonName: O,
                            previewScreenNormal: w,
                            setPreviewScreenNormal: C,
                            device: N,
                            setDevice: M
                        },
                        children: Object(Qe.jsxs)(l.a, {
                            className: "App d-flex flex-column min-vh-100 vh-100",
                            children: [Object(Qe.jsx)(d.a, {
                                className: "header",
                                children: Object(Qe.jsx)(Ve, {})
                            }), Object(Qe.jsxs)(d.a, {
                                className: "main",
                                children: [Object(Qe.jsx)(c.a, {
                                    xs: 6,
                                    className: "leftcol",
                                    children: Object(Qe.jsx)(Kt, {})
                                }), Object(Qe.jsx)(c.a, {
                                    xs: 6,
                                    className: "rightcol",
                                    children: Object(Qe.jsx)(Gn, {})
                                })]
                            })]
                        })
                    })
                },
                Qn = function(e) {
                    e && e instanceof Function && n.e(3).then(n.bind(null, 31)).then((function(t) {
                        var n = t.getCLS,
                            a = t.getFID,
                            i = t.getFCP,
                            o = t.getLCP,
                            s = t.getTTFB;
                        n(e), a(e), i(e), o(e), s(e)
                    }))
                };
            s.a.render(Object(Qe.jsx)(i.a.StrictMode, {
                children: Object(Qe.jsx)(_n, {})
            }), document.getElementById("root")), Qn()
        }
    },
    [
        [25, 1, 2]
    ]
]);
//# sourceMappingURL=main.b93b9582.chunk.js.map